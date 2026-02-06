# MacOS Setup
A guide for setting up the local development environment.

## Using the Brewfile
The **Brewfile** allows you to install all command-line tools and applications at once.

### Installation Steps:
1.  **Save the file:** Save the file named **Brewfile** (no extension) in your current directory and paste the contents into it.
2.  **Run the install:** Execute the following command in your terminal:
    ```bash
    brew bundle
    ```
3.  **Verify:** To check if everything was installed successfully, run:
    ```bash
    brew bundle check
    ```