# Quiz Contribution

Welcome to the Quiz project! This repository is designed to collect simple quiz questions on various topics. By contributing, you can help others learn and also participate in Hacktoberfest.

## How to Contribute

Follow these steps to contribute your questions:

### 0. Create an Issue

Create an issue in the original repository. We will tag it as Hacktoberfest and assign it to you.

Sample issue:

```md
I think we need to add more git questions in [here](https://github.com/GDG-Caldwell/Quiz/blob/main/Git/questions.md)

I can add 2 questions and will follow the format given in [ReadMe](https://github.com/GDG-Caldwell/Quiz/blob/main/README.md#4-add-questions)
```

### 1. Fork the Repository

First, fork this repository to your own GitHub account.

### 2. Clone the Repository

Clone the forked repository to your local machine:

```bash
git clone https://github.com/GDG-Caldwell/Quiz.git
cd Quiz
```

### 3. Create a New Branch

Create a new branch for your contributions:

```bash
git checkout -b add-questions
```

### 4. Add questions

Open the `questions.md` file in your favorite text editor and add your questions. Each topic should have 20 simple questions. Follow the format below:

```md
# Topic Title

## Question 1

**Your question here?**

- [ ] A. Option 1
- [ ] B. Option 2
- [x] C. Correct Option
- [ ] D. Option 4

## Question 2

**Your question here?**

- [ ] A. Option 1
- [x] B. Correct Option
- [ ] C. Option 3
- [ ] D. Option 4

... up to 20 questions
```

### 5. Commit Your Changes

After adding your questions, commit your changes:

```bash
git add .
git commit -m "Add questions for [Topic]"
```

### 6. Push Your Changes

```bash
git push origin add-questions
```

### 7. Create a Pull Request

Go to the original repository on GitHub and create a pull request from your forked repository. Provide a clear description of the changes you made.

## Hacktoberfest Participation

By contributing to this repository, you can participate in Hacktoberfest. Make sure to register on the [Hacktoberfest website]('https://hacktoberfest.com') and follow the rules to earn your Hacktoberfest rewards.

Happy contributing!
