  
class SoftwareEngineer {
    constructor() {
        this.name = "Marko";
        this.role = "Software Development Student";
        this.languages = ["HTML/CSS" "??", "???", ];
        this.interests = ["Web Development", "??", "???"];
        this.socialMedia = {
            LinkedIn: "linkedin.com/in/marko-villemson",
            GitHub: "github.com/Villemson"
        };
    }

    introduceSelf() {
        console.log(`Hi there! My name is ${this.name}. I'm a ${this.role}, passionate about coding and exploring new technologies.`);
        console.log("Here are a few things about me:");
        console.log("- I enjoy learning new programming languages and frameworks.");
        console.log("- My current interests include web development, ??, and ???.");
        console.log("- I love collaborating with others and sharing knowledge.");
        console.log("You can connect with me on the following platforms:");
        for (let platform in this.socialMedia) {
            console.log(`- ${platform}: ${this.socialMedia[platform]}`);
        }
    }
}

let me = new SoftwareEngineer();
me.introduceSelf();
