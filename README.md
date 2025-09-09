``` javascript
class Developer {
    constructor() {
        this.name = "Mehedi Hasan";
        this.role = "WEB Developer";
        this.language_spoken = ["bn_BD", "en_US"];
    }

    introduce() {
        console.log(`Hi, I'm ${this.name}, a ${this.role}.`);
    }
}

const dev = new Developer();
dev.introduce();

```
