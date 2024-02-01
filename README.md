# MadLib Code

This simple Python script generates a madlib based on user input for verbs and duration. Madlibs are a fun way to create humorous and often nonsensical sentences by filling in the blanks with user-provided words.

## How to Use

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/madlib-generator.git
    ```

2. Navigate to the project directory:

    ```bash
    cd madlib-generator
    ```

3. Run the script:

    ```bash
    python madlib.py
    ```

4. Follow the prompts to enter verbs and a duration.

5. The script will generate a madlib sentence and print it to the console.

## Example
```python
verb = input("Verb: ")
duration = input("Duration(e.g; five hours): ")
verb1 = input("Verb: ")

madlib = f"Coding is fun and that's why I {verb} it. It keeps me \
occupied for {duration} every day.{verb1} is like magic!!"

print(madlib)
```

## Input Example
```
Verb: love
Duration(e.g; five hours): seven days
Verb: enjoy
```

## Output Example
```
Coding is fun and that's why I love it. It keeps me occupied for seven days every day. Enjoy is like magic!!
```

Feel free to modify and use this script as needed!
