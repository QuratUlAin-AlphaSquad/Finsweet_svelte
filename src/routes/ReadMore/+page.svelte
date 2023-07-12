<script>
    import Footer from "../Components/Footer.svelte";
    import NavBar from "../Components/NavBar.svelte";
</script>

<NavBar />

<main class="content">
    <div class="UXCaseStudy">
        <p class="Andrew1">
            A UX Case Study on Creating a Studious Environment for Students
        </p>
    </div>
    <div>
        <p class="Andrew2">
            Andrew Jonson <span class="postedOn">
                Posted on 27th January 2021</span
            >
        </p>
    </div>
    <div class="contentImg">
        <img
            src="../images/people-working-in-front-of-computer-3182763.png"
            alt=""
        />
    </div>
    <div class="staticContent">
        <p class="LoremHeading">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit.
        </p>
        <p class="LoremPara">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
            eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim
            ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut
            aliquip ex ea commodo consequat. Duis aute irure dolor in
            reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla
            pariatur. Excepteur sint occaecat cupidatat non proident, sunt in
            culpa qui officia deserunt mollit anim id est laborum. Ut enim ad
            minim veniam, quis nostrud exercitation ullamco laboris nisi ut
            aliquip ex ea commodo consequat. Duis aute irure dolor in
            reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla
            pariatur. Excepteur sint occaecat cupidatat non proident, sunt in
            culpa qui officia deserunt mollit anim id est laborum.
        </p>
        <p class="LoremHeading">Ut enim ad minim veniam, quis nostrud.</p>
        <p class="LoremPara">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
            eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim
            ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut
            aliquip ex ea commodo consequat. Duis aute irure dolor in
            reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla
            pariatur. Excepteur sint occaecat cupidatat non proident, sunt in
            culpa qui officia deserunt mollit anim id est laborum. Ut enim ad
            minim veniam, quis nostrud exercitation ullamco laboris nisi ut
            aliquip ex ea commodo consequat. Duis aute irure dolor in
            reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla
            pariatur. Excepteur sint occaecat cupidatat non proident, sunt in
            culpa qui officia deserunt mollit anim id est laborum.
        </p>
        <ul>
            <li>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do.
            </li>
            <li>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do.
            </li>
            <li>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do.
            </li>
        </ul>
        <p class="LoremPara">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
            eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim
            ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut
            aliquip ex ea commodo consequat. Duis aute irure dolor in
            reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla
            pariatur. Excepteur sint occaecat cupidatat non proident, sunt in
            culpa qui officia deserunt mollit anim id est laborum. Ut enim ad
            minim veniam, quis nostrud exercitation ullamco laboris nisi ut
            aliquip ex ea commodo consequat. Duis aute irure dolor in
            reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla
            pariatur. Excepteur sint occaecat cupidatat non proident, sunt in
            culpa qui officia deserunt mollit anim id est laborum.
        </p>
        <img src="../images/ReadBlog.jpg" alt="" />
        <p class="LoremHeading">Ut enim ad minim veniam, quis nostrud.</p>
        <p class="LoremPara">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
            eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim
            ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut
            aliquip ex ea commodo consequat. Duis aute irure dolor in
            reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla
            pariatur. Excepteur sint occaecat cupidatat non proident, sunt in
            culpa qui officia deserunt mollit anim id est laborum. Ut enim ad
            minim veniam, quis nostrud exercitation ullamco laboris nisi ut
            aliquip ex ea commodo consequat. Duis aute irure dolor in
            reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla
            pariatur. Excepteur sint occaecat cupidatat non proident, sunt in
            culpa qui officia deserunt mollit anim id est laborum.
        </p>
    </div>
    <Footer />
</main>

<style>
    .UXCaseStudy {
        display: flex;
        max-width: 949px;
        width: 100%;
        align-items: center;
        justify-content: center;
    }
    .Andrew1 {
        color: var(--dark-blue, #282938);
        text-align: center;

        font-family: Poppins;
        font-size: 48px;
        font-style: normal;
        font-weight: 600;
        line-height: 64px;
    }
    .Andrew2 {
        color: var(--dark-blue, #282938);
        text-align: center;

        /* Label 2 */
        font-family: Poppins;
        font-size: 16px;
        font-style: normal;
        font-weight: 500;
        line-height: 28px;
    }
    .content {
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        margin-top: 128px;
    }
    .LoremHeading {
        /* display: flex; */
        max-width: 840px;
        /* text-align: left; */
        /* flex-direction: column; */
        /* flex-shrink: 0; */

        color: var(--dark-blue, #282938);

        /* Heading 3 */
        font-family: Poppins;
        font-size: 38px;
        font-style: normal;
        font-weight: 600;
        line-height: 56px;
    }
    .LoremPara {
        /* display: flex; */
        max-width: 840px;

        color: #282938;

        font-size: 16px;
        font-style: normal;
        font-weight: 400;
        line-height: 28px;
    }
    .staticContent {
        display: flex;
        flex-direction: column;
        align-items: flex-start;
    }
</style>
