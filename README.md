Change the base of the weights by adding --shift-base arguemnt to any run. Example:
    ```
    python mnist.py --shift-depth 3 --shift-type PS --optimizer radam --shift-base 4
    ```
Only use power of two as bases for meaningful results
