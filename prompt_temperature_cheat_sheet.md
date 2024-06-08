# Large Language Model prompt temperature Cheat Sheet

## Temperature Settings

- **0.1 - 0.2:** Best for deterministic tasks requiring precise and accurate outputs.
- **0.2 - 0.3:** Suitable for tasks needing a balance between creativity and accuracy.
- **0.3 - 0.4:** Ideal for creative tasks that benefit from a bit of randomness.
- **0.4 - 0.5:** Use for highly creative and exploratory tasks.

### 1. **Basic Syntax and Simple Code Snippets**

- **Temperature:** 0.1 - 0.2
- **Description:** Simple functions and basic programming constructs.
- **Prompt Example:** "Write a Python function to check if a number is even."

### 2. **Algorithm Implementation (e.g., Sorting, Searching)**

- **Temperature:** 0.1 - 0.2
- **Description:** Implementing standard algorithms in various programming languages.
- **Prompt Example:** "Implement the quicksort algorithm in JavaScript."

### 3. **Code Debugging and Error Fixing**

- **Temperature:** 0.1 - 0.2
- **Description:** Identifying and fixing syntax or logical errors in code.
- **Prompt Example:** "Fix the following Python code to remove syntax errors:\n`python\ndef add(a, b):\nprint(a + b\n`"

### 4. **API Usage Examples**

- **Temperature:** 0.2 - 0.3
- **Description:** Demonstrating how to use various APIs in different programming languages.
- **Prompt Example:** "Show an example of how to use the requests library in Python to make a GET request."

### 5. **Complex Function Implementations (e.g., Machine Learning Algorithms)**

- **Temperature:** 0.2 - 0.3
- **Description:** Writing more complex functions, such as machine learning algorithms.
- **Prompt Example:** "Write a Python function to implement the k-means clustering algorithm."

### 6. **Code Refactoring and Optimization**

- **Temperature:** 0.2 - 0.3
- **Description:** Improving the efficiency and readability of existing code.
- **Prompt Example:** "Refactor the following Java code to improve its performance:\n`java\npublic int sum(int[] numbers) {\n    int total = 0;\n    for (int i = 0; i < numbers.length; i++) {\n        total += numbers[i];\n    }\n    return total;\n}\n`"

### 7. **Creative Coding (e.g., Generative Art, Game Development)**

- **Temperature:** 0.3 - 0.4
- **Description:** Writing code for creative projects like generative art or simple games.
- **Prompt Example:** "Create a simple generative art piece using p5.js that draws random circles on the canvas."

### 8. **Documentation and Code Comments**

- **Temperature:** 0.3 - 0.4
- **Description:** Adding comments and documentation to explain code.
- **Prompt Example:** "Add comments to the following Python function to explain what each part does:\n`python\ndef factorial(n):\n    if n == 0:\n        return 1\n    else:\n        return n * factorial(n-1)\n`"

### 9. **Unit Test Generation**

- **Temperature:** 0.2 - 0.3
- **Description:** Writing unit tests to verify the functionality of code.
- **Prompt Example:** "Write unit tests for the following JavaScript function using Jest:\n`javascript\nfunction add(a, b) {\n    return a + b;\n}\n`"

### 10. **Exploratory Data Analysis (EDA) Code**

- **Temperature:** 0.2 - 0.3
- **Description:** Writing scripts to perform EDA on datasets.
- **Prompt Example:** "Write a Python script to perform exploratory data analysis on a CSV file using pandas."

### 11. **Configuration File Generation (e.g., YAML, JSON)**

- **Temperature:** 0.1 - 0.2
- **Description:** Generating configuration files in various formats.
- **Prompt Example:** "Generate a sample YAML configuration file for a web server."

### 12. **Scripting for Automation (e.g., Shell Scripts, Python Scripts)**

- **Temperature:** 0.2 - 0.3
- **Description:** Writing scripts to automate repetitive tasks.
- **Prompt Example:** "Write a Bash script to back up a directory to a remote server using rsync."

### 13. **Interactive Tutorials and Learning Resources**

- **Temperature:** 0.3 - 0.4
- **Description:** Creating step-by-step tutorials and educational content.
- **Prompt Example:** "Create a step-by-step tutorial for beginners on how to set up a React project."

### 14. **Code Reviews and Suggestions**

- **Temperature:** 0.2 - 0.3
- **Description:** Reviewing code and providing suggestions for improvement.
- **Prompt Example:** "Review the following Python code and suggest improvements:\n`python\ndef find_max(numbers):\n    max_num = numbers[0]\n    for num in numbers:\n        if num > max_num:\n            max_num = num\n    return max_num\n`"

### 15. **Creative Writing in Code (e.g., Code Poetry)**

- **Temperature:** 0.4 - 0.5
- **Description:** Writing code that is artistic or poetic in nature.
- **Prompt Example:** "Write a piece of code poetry in Python that expresses the beauty of recursion."

---

This version includes more detailed explanations and maintains a consistent format, making it easier to understand and use.
