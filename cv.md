## Daniil Dashkevich

---

### About Me

| I am a passionate and motivated junior developer with 4 months of experience. My goal is to continue learning and growing in the field of web development. I thrive on challenges and enjoy solving problems. My curiosity drives me to explore new technologies and stay up-to-date with industry trends.   | ![Фотография](assets/photo_2023-08-11_18-49-58.jpg) | 
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------|

---

### Location

Accommodation: Belarus, Minsk

Operational readiness: Ready for remote operation

### Age and seniority

Experience: 4 months

Age: 18 years

### Contact Information

Phone: +375447563953

Telegram: @guffinnn

Email: danidashkevichit@gmail.com

My resume on Habr career: [Frontend developer](https://career.habr.com/guffinnn)

My account on GitHub: [guffinnn](https://github.com/guffinnn)

My portfolio on Behance: [daniildashkev](https://www.behance.net/daniildashkev)


### Languages

1. English: Intermediate (B2+)
2. Russian: Native
3. Belarus: Native

### Professional Skills

- Web development
- Adaptive layout
- Crosspost
- API design
- Databases
- SRS
- Modeling of systems and processes
- Prototyping
- OOP
- Flexible development methodologies
- Manual testing

### Code Samples

#### Smallest possible sum (4 kyu)

[Link on CodeWars](https://www.codewars.com/kata/52f677797c461daaf7000740)

    function solution(numbers) {
        let gcd = (a, b) => b ? gcd(b, a % b) : a;
        return numbers.reduce(gcd) * numbers.length;
    }

#### Fun with trees: array to tree (5 kyu)

[Link on CodeWars](https://www.codewars.com/kata/57e5a6a67fbcc9ba900021cd)

    function arrayToTree(array) {
        if (array.length === 0) return undefined;
        let nodes = array.map(value => new TreeNode(value));
        for (let i = 0; i < nodes.length; i++) {
            nodes[i].left = nodes[2 * i + 1];
            nodes[i].right = nodes[2 * i + 2];
        }
        return nodes[0];
    }