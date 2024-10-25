- 👋 Hi, I’m @monadalavi
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
monadalavi/monadalavi is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
unction calculateBMI(weight, height) {
    // Write your code here
    //  check if both values are positive   
    if (height > 0 && weight > 0) {
        const bmi = weight / (height * height);

        if (bmi < 18.5) {
            return "Underweight";
        } else if (bmi >= 18.5 && bmi < 24.9) {
            return "Normal weight";
        } else if (bmi >= 25 && bmi < 29.9) {
            return "Overweight";
        } else {
            return "Obese";
        }
    }
    else
    {
        return 'Height and Weight should bea positive value';
    }
}

// Do not modify the below lines
module.exports = { calculateBMI };
