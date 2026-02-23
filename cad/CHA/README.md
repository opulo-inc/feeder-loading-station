Generating Wireviz Drawings

1. Install `uv` if you haven't already:

    ```
    curl -LsSf https://astral.sh/uv/install.sh | sh
    ```

2. In terminal, cd into the CHA folder.

3. Run:

    ```
    uv venv
    uv sync
    ```

4. You now have wireviz installed in this folder. You can generate wirevis drawings from source using:

    ```
    uv run wireviz example-cable/example-cable.yml
    ```