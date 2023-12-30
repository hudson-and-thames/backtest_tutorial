# Setting Up a Python Virtual Environment and Installing Dependencies

In this guide, we'll walk through the steps to create a Python virtual environment and install the necessary libraries for our financial analysis project. Virtual environments in Python are a tool to keep dependencies required by different projects in separate places. This is achieved by creating isolated python virtual environments for them.

## Step 1: Install Virtualenv
First, ensure that you have `virtualenv` installed. If you don't have `virtualenv` installed, you can install it using pip:

```bash
pip install virtualenv
```

## Step 2: Create a Virtual Environment
Navigate to your project's directory in the terminal and run the following command to create a virtual environment. Replace `myenv` with your desired environment name.

```bash
virtualenv myenv
```

## Step 3: Activate the Virtual Environment
Once the environment is created, you need to activate it. The command to activate the virtual environment varies based on your operating system.

- On Windows:
    ```bash
    .\myenv\Scripts\activate
    ```

- On macOS and Linux:
    ```bash
    source myenv/bin/activate
    ```

## Step 4: Install Dependencies
With your environment activated, you can now install the required libraries. Run the following commands to install `numpy`, `pandas`, `yfinance`, `quantstats`, and `matplotlib`:

```bash
pip install -r requirements.txt
```

## Step 5: Verify Installation
After installation, you can verify that the packages are installed correctly in your virtual environment by running:

```bash
pip list
```

This will show you a list of all installed packages and their versions in your virtual environment.

## Step 6: Deactivating the Virtual Environment
Once you're done working in the virtual environment, you can deactivate it by running:

```bash
deactivate
```

This command will return you to your global Python environment.

---
