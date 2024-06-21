<style>
    @import url('https://fonts.googleapis.com/css2?family=Inter:wght@100..900&family=Jost:ital,wght@0,100..900;1,100..900&family=Montserrat+Alternates:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');


    /* ===== main ===== */
    a {
        color: #FFFFFF75;
        text-decoration: none;
        transition: all 0.2s linear;
    }

    a:hover {
        font-size: 101%;
        color: #FFFFFF90;
    }

    img {
        user-select: none;
        pointer-events: none;
    }


    /* ===== wrapper ===== */
    .wrapper {
        display: flex;
        align-items: center;
        flex-direction: column;
        justify-content: center;

        padding: 2vh;
        text-align: center;
        background-color: #400082;
    }

    .inner-wrapper {
        display: flex;
        align-items: center;
        flex-direction: column;
        justify-content: center;

        width: auto;
        height: auto;

        color: #FFFFFF50;
        font-size: 16px;
        font-weight: 500;
        font-family: 'Jost', sans-serif;

        padding: 2vh;
        text-align: center;
        position: relative;
        box-sizing: border-box;
    }

    .inner-wrapper::before {
        top: 0;
        left: 0;
        content: "";
        z-index: 0;
        position: absolute;

        width: 100%;
        height: 100%;

        border-radius: 8px;
        border: solid 1px #FFFFFF20;

        opacity: 0.3;
        box-sizing: border-box;
        transition: all 0.2s linear;
        background: linear-gradient(to bottom, rgba(255, 255, 255, 0.7) 0%, rgba(255, 255, 255, 0.5) 100%);
    }


    /* ===== badges ===== */
    .badges {
        z-index: 1;

        gap: 5px;
        display: flex;
        align-items: center;
        flex-direction: column;
        justify-content: center;
    }

    .badges div {
        gap: 15px;
        display: flex;
        align-items: center;
        justify-content: center;
    }

    .badges div span {
        cursor: pointer;
    }


    /* ===== about me ===== */
    .about_me {
        z-index: 1;

        gap: 0.7vh;
        display: flex;
        align-items: center;
        flex-direction: column;
        justify-content: center;

        color: #FFFFFF75;
        font-size: 18px;
        font-weight: 600;
        font-family: 'Montserrat Alternates', sans-serif;
    }

    .about_me div {
        gap: 1vh;
        display: flex;
        align-items: center;
        justify-content: center;
    }

    .about_me div span { cursor: pointer; }


    /* ===== components ===== */
    .header {
        z-index: 1;

        font-size: 32px;
        font-weight: 500;
        font-family: 'Montserrat Alternates', sans-serif;
    }

    .separator {
        width: 100%;
        height: 0.3vh;

        float:left;
        margin: 1.5vh;
        background-color:#FFFFFF10;
    }
</style>

<div class="wrapper">
    <div class="inner-wrapper">
        <div class="header">
            <span>greet you, i am <a href="https://vk.com/id632239559">Daniil</a> <img src="https://github.com/blackcater/blackcater/raw/main/images/Hi.gif" height="32px" alt="wave-emoji"></span>
        </div>
        <h2>i live in Russia, from languages I know Russian and a little English</h2>

        <span class="separator"></span>

        <div class="about_me">
            <span>I love programming and I really enjoy it!</span>
            <span>I started doing it when I was 13 years old and I have a lot of experience.</span>
            <span>You may know me from such projects as:</span>

            <div>
                <span>
                    <img src="https://img.shields.io/badge/Farmilkin-000000.svg?style=for-the-badge" alt="lua-badge">
                </span>
                <span onclick="window.open('https://vk.com/arp_forum_parser', '_blank')">
                    <img src="https://img.shields.io/badge/ForumParser-000000.svg?style=for-the-badge" alt="lua-badge">
                </span>
            </div>
        </div>

        <span class="separator"></span>
        <div class="badges">
            <span>my stack</span>
            <div>
                <img src="https://img.shields.io/badge/lua-%232C2D72.svg?style=for-the-badge&logo=lua&logoColor=white" alt="lua-badge">
                <img src="https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white" alt="cpp-badge">
                <img src="https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white" alt="node_js-badge">
                <img src="https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB" alt="react-badge">
                <img src="https://img.shields.io/badge/react_native-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB" alt="react_native-badge">
            </div>
        </div>

        <span class="separator"></span>
        <div class="badges">
            <span>my profiles on the forums</span>
            <div>
                <span onclick="window.open('https://www.blast.hk/members/458823/', '_blank')">
                    <img src="https://img.shields.io/badge/blasthack-%2300599C.svg?style=for-the-badge&logo=codeforces&logoColor=white" alt="blasthack-badge">
                </span>
                <span onclick="window.open('https://www.unknowncheats.me/forum/members/6205766.html', '_blank')">
                    <img src="https://img.shields.io/badge/unknowncheats-28242c.svg?style=for-the-badge&logo=codeforces&logoColor=white" alt="unknowncheats-badge">
                </span>
            </div>
        </div>

        <span class="separator"></span>
        <div class="badges">
            <span>you can reach me with</span>
            <div>
                <span onclick="window.open('https://t.me/dgsrsv', '_blank')">
                    <img src="https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="telegram-badge">
                </span>
                <span onclick="window.open('https://discord.gg/bCy2zGdNyY', '_blank')">
                    <img src="https://img.shields.io/badge/Discord-%235865F2.svg?style=for-the-badge&logo=discord&logoColor=white" alt="discord-badge">
                </span>
                <span onclick="window.open('https://vk.com/id632239559', '_blank')">
                    <img src="https://img.shields.io/badge/ВКонтакте-0775f9?style=for-the-badge" alt="vkontakte-badge">
                </span>
            </div>
        </div>
    </div>
</div>


<!--
**dgsrsv/dgsrsv** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
