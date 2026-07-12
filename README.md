# CV 📄

Cross-platform instructions to render the final document:

- Ensure you have the right [.python-version](.python-version) and create a virtual environment:

  ```bash
  python3 -m venv venv/
  ```

- Activate it:

  - **Linux:**

    ```bash
    source venv/bin/activate
    ```

  - **Windows (Command Prompt):**

    ```bat
    venv\Scripts\activate.bat
    ```

  - **Windows (PowerShell):**

    ```powershell
    venv\Scripts\Activate.ps1
    ```

- Install RenderCV:

  ```bash
  pip install "rendercv[full]==2.8"
  ```

- Render the output:

    ```bash
    rendercv render src/cv.yaml --dont-generate-markdown --dont-generate-html --dont-generate-png --typst-path ../out/cv.typ --pdf-path ../out/cv.pdf
    ```
