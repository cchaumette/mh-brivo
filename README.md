# mh-brivo
## Download and Install Miniconda

1. **Download Miniconda**: Go to the [Miniconda website](https://docs.conda.io/en/latest/miniconda.html) in your web browser.

2. **Choose Windows Installer**: Choose the Windows installer that corresponds to your system (32-bit or 64-bit). Click the link to download the installer.

3. **Run the Installer**: Double-click the downloaded installer executable (e.g., `Miniconda3-latest-Windows-x86_64.exe`) to start the installation.

4. **Follow Installation Steps**: Follow the on-screen instructions to install Miniconda. You can choose the installation directory and whether to add Miniconda to your PATH. Select the options that suit your preferences.

## Git clone this repo or Download YAML File

1. **Open Anaconda Prompt**: Press `Win + R`, type `cmd`, and press Enter to open the Anaconda Prompt.

2. **Navigate to YAML File Directory**: Use the `cd` command to navigate to the directory containing `env.yml`.

3. **Create the Environment**: Run the following command to create the environment: `conda env create -f env.yml`

## Step 3: Activate the Environment and Run Jupyter Notebook

1. **Activate the Environment**: In the Anaconda Prompt, activate the newly created environment:`conda activate mh-brivo`

2. **Launch Jupyter Notebook**: With the environment activated, run the following command to launch Jupyter Notebook: `jupyter notebook`

3. **Your web browser will open with the Jupyter Notebook interface. Open brivo-api.ipynb
