# Intro to BPL

I made these 16 SolveIt notebooks while learning BasedPL (BPL), an array programming language. Each notebook works through a topic from the [official BasedPL documentation](https://answerdotai.github.io/basedpl/) with examples I tried, questions I asked, and saved results.

## Notebooks

1. [Working with Lists](notebooks/01%20Working%20with%20Lists.ipynb)
2. [Shapes and Nesting](notebooks/02%20Shapes%20and%20Nesting.ipynb)
3. [Numbers](notebooks/03%20Numbers.ipynb)
4. [Text and Strings](notebooks/04%20Text%20and%20Strings.ipynb)
5. [Sets and Searching](notebooks/05%20Sets%20and%20Searching.ipynb)
6. [Trains and Operators](notebooks/06%20Trains%20and%20Operators.ipynb)
7. [Writing Dfns](notebooks/07%20Writing%20Dfns.ipynb)
8. [Records and Tables](notebooks/08%20Records%20and%20Tables.ipynb)
9. [Files and Python](notebooks/09%20Files%20and%20Python.ipynb)
10. [Repeating Things](notebooks/10%20Repeating%20Things.ipynb)
11. [Windows and Neighbours](notebooks/11%20Windows%20and%20Neighbours.ipynb)
12. [Linear Algebra](notebooks/12%20Linear%20Algebra.ipynb)
13. [Index Notation](notebooks/13%20Index%20Notation.ipynb)
14. [Autodiff and ML](notebooks/14%20Autodiff%20and%20ML.ipynb)
15. [Plotting and Pictures](notebooks/15%20Plotting%20and%20Pictures.ipynb)
16. [Bigger Dfns](notebooks/16%20Bigger%20Dfns.ipynb)

## Running the Examples

Open any notebook on GitHub to read the notes and saved results. To experiment, download the notebooks from the repository's **Code** menu and import them into SolveIt, or open them with a Python kernel in Jupyter.

Run the setup cells to install BasedPL and load its notebook extension. The examples use the `%%bpl` cell magic. The saved runs used BasedPL 0.1.90 and 0.1.91. The setup cells may install a newer release. If you're using Jupyter, skip the SolveIt-specific `%%prompt` cells in notebooks 05 and 12.

Run notebook 09 in a fresh working directory. Its examples create `bpl-files` and remove it at the end.

## Sources

The notebooks adapt examples from [AnswerDotAI's BasedPL documentation and source repository](https://github.com/AnswerDotAI/basedpl). The [upstream Apache 2.0 licence](third-party/basedpl/LICENSE) is included for that material.
