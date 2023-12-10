# Bank_Marketing_Subscription_Model
"Bank Marketing Dataset" related to direct marketing campaigns of a Portuguese banking institution. This dataset involves predicting whether a client will subscribe to a term deposit based on various features.

Relevance to Marketing: The dataset involves marketing campaigns, and you can explore strategies to optimize marketing efforts for better subscription rates.

Predictive Modeling: You can build predictive models to understand which factors influence clients' decisions to subscribe to a term deposit, allowing you to optimize marketing strategies.

Business Impact: Successfully predicting customer behavior in marketing campaigns can have a direct impact on revenue operations, helping the bank allocate resources more effectively.

Practical Applications: The insights gained from this project can be directly applied to real-world marketing scenarios, making it a valuable experience for someone interested in Sales and Marketing.


## Set up your Environment


### **`macOS`** type the following commands : 

- For installing the virtual environment you can either use the [Makefile](Makefile) and run `make setup` or install it manually with the following commands:

     ```BASH
    make setup
    ```
    After that active your environment by following commands:
    ```BASH
    source .venv/bin/activate
    ```
Or ....
- Install the virtual environment and the required packages by following commands:

    ```BASH
    pyenv local 3.11.3
    python -m venv .venv
    source .venv/bin/activate
    pip install --upgrade pip
    pip install -r requirements.txt
    ```
    
### **`WindowsOS`** type the following commands :

- Install the virtual environment and the required packages by following commands.

   For `PowerShell` CLI :

    ```PowerShell
    pyenv local 3.11.3
    python -m venv .venv
    .venv\Scripts\Activate.ps1
    pip install --upgrade pip
    pip install -r requirements.txt
    ```

    For `Git-bash` CLI :
    ```
    pyenv local 3.11.3
    python -m venv .venv
    source .venv/Scripts/activate
    pip install --upgrade pip
    pip install -r requirements.txt
    ```

    **`Note:`**
    If you encounter an error when trying to run `pip install --upgrade pip`, try using the following command:
    ```Bash
    python.exe -m pip install --upgrade pip
    ```
