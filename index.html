// ==========================================
// NAVIGATION + ACTIVE LINK
// ==========================================

const sections = document.querySelectorAll("section");
const navLinks = document.querySelectorAll("nav a");

// ------------------------------------------
// NAVIGATION CLICK
// ------------------------------------------

navLinks.forEach(link => {

    link.addEventListener("click", function (event) {

        const targetId = this.getAttribute("href");

        // Ignore external links and resume link
        if (!targetId || !targetId.startsWith("#")) {
            return;
        }

        const targetSection = document.querySelector(targetId);

        if (targetSection) {

            event.preventDefault();

            targetSection.scrollIntoView({
                behavior: "smooth",
                block: "start"
            });

            // Update URL hash
            history.pushState(null, "", targetId);
        }

    });

});


// ------------------------------------------
// ACTIVE NAVIGATION LINK
// ------------------------------------------

window.addEventListener("scroll", () => {

    let current = "";

    sections.forEach(section => {

        const sectionTop = section.offsetTop - 150;
        const sectionHeight = section.offsetHeight;

        if (
            window.scrollY >= sectionTop &&
            window.scrollY < sectionTop + sectionHeight
        ) {

            current = section.getAttribute("id");

        }

    });


    navLinks.forEach(link => {

        link.classList.remove("active");

        if (
            link.getAttribute("href") === "#" + current
        ) {

            link.classList.add("active");

        }

    });

});