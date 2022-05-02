# Pychain Challenge

The purpose of this challenge to build a blockchain-based ledger system, complete with a user-friendly web interface. This ledger should allow partner banks to conduct financial transactions (that is, to transfer money between senders and receivers) and to verify the integrity of the data in the ledger.

---

## Technologies

The credit risk resampling analysis leverages Python 3.8+ and utilizes the following project libraries and dependencies:
* [Streamlit](https://streamlit.io/) - a Python library that turns Python scripts into shareable web apps
* [Pandas](https://pandas.pydata.org/) - a software library designed for open source data analysis and manipulation
* dataclasses
* typing
* hashlib


---

## Installation Guide


Download Anaconda for your operating system and the latest Python version, run the installer, and follow the steps. Restart the terminal after completing the installation. Detailed instructions on how to install Anaconda can be found in the [Anaconda documentation](https://docs.anaconda.com/anaconda/install/).

This challenge utilizes Streamlit to create a user-friendly webpage interface for a blockchain. To import Streamlit, run the following command:

```python
pip install streamlit
```

---

## Usage
The analysis is hosted on the following GitHub repository at: https://github.com/nguyenthuyt/pychain   

### **Run instructions:**
To run this analysis, simply clone the repository or download the files. Open a terminal instance and navigate to the directory that contains the **pychain.py** file, and then run the following command:
```python
streamlit run pychain.py
```
___
## Streamlit User Interface

Utilizing the Streamlit interface, the user is able to enter sender, receiver, and amount details and click on 'Add Block' to create a new block. A block inspector is available on the left-hand side to verify the block has been added or to review all blocks stored in the ledger. 

![Pychain Blocks](Images/blocks.PNG)

The Streamlit interface also allows the user to test the blockchain validation process by clicking on the 'Validate Chain' button. Once doing so, a 'True' response should be returned.

![Pychain Ledger Validation](Images/validation.PNG)



---

## Contributors

This project was created as part of the Rice Fintech Bootcamp 2022 Program by:

Thuy Nguyen

Email: nguyen_thuyt@yahoo.com

LinkedIn: nguyenthuyt



---

## License

MIT




