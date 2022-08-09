# Challenge-18

This Challenge showed a simple to use, web app for a blockchain-based ledger system. This ledger should allow partner banks to conduct financial transactions (that is, to transfer money between senders and receivers) and to verify the integrity of the data in the ledger.
_________________________

# Installation Guide
run pip install -r requirements.txt
_________________________

# Technologies
import streamlit as st from dataclasses import dataclass from typing import Any, List import datetime as datetime import pandas as pd import hashlib
_________________________

# Usage
Run the following command: streamlit run pychain.py

The Streamlit application will run locally in your browser and should launch automatically.

![pychain](https://user-images.githubusercontent.com/100783805/183780049-1a7e6f5a-7aa5-4b60-9798-0d14b1b577ad.png)
![pychain2](https://user-images.githubusercontent.com/100783805/183780057-f28b18ba-827a-4b91-9939-ee74b94ba3e7.png)


_________________________

# Validation
Once additional blocks have been addeed to the chain, clicking the 'Validate Chain' button will produce a True statement indicating the validity of the entire ledger.
_________________________

# Contributors
Aarchit Malhotra 
_________________________

# License
This code is exclusive to those who are provided a direct access. A user-key feature can be added later
