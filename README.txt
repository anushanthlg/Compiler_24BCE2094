# SLR(1) Parser
## Step by Step Compiler Design Lab

**Team Members:**
- Anushanth L G — 24BCE2094
- Niraj Kanna — 24BCE2324

**Course:** Compiler Design Lab  
**Slot:** L37 + L38

### Open the Application

**Online:** [SLR(1) Parser](https://claude.ai/artifact/XiLWtpewKGKkncjFG71BFA)

**Offline:** Double-click `SLR-Parser.html` to open it in any web browser. The application works offline; fonts require an internet connection.

## How to Use

1. **Enter the grammar:** Type your grammar, one production per row. A new row appears as you type.

   Example:
   ```
   S -> AA
   A -> aA | b
   ```

2. **Enter the input string:** Type the string you want to parse.

   Example: `aabb`

3. **Build the parser:** Click **Build parser** to generate the parser.

4. **Learn step by step:** Click **Next step** to construct FIRST and FOLLOW sets, LR(0) item sets, and the SLR(1) parsing table. Check for conflicts and follow the parsing process step by step, with explanations for each stage.

5. **Practice:** Complete the worksheet yourself, then click **Check** for each section to verify your answers. Incorrect entries are marked with explanations. Use **Show answer** to reveal the correct answers.

## Project Structure

- `SLR-Parser.html` — The standalone application.
- `docs/` — Design documentation and viva questions.
- `source/` — Source code, including the application engine and tests.

### Running the Tests

Run the following command from the project directory:

```bash
node source/tests/run-tests.js
```
