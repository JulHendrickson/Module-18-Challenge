# Module 18 Challenge

For this challenge, I built a blockchain-based ledger system, complete with a user-friendly web interface. This ledger could institutions to conduct financial transactions (transfer money between senders and receivers) and to verify the integrity of the data in the ledger.

I made updates to the provided Python file that included:

1. Creating a new data class named `Record`. This class serves as the blueprint for transaction records that the blocks of the ledger will store.

2. Modified the existing `Block` data class to store `Record` data.

3. Added Relevant User Inputs to the Streamlit interface.

4. Tested the PyChain Ledger by Storing Records.

### Working application

The application can be opened by running the command "streamlit run pychain.py" from the command terminal.

![Application_Page_code_corrected](https://github.com/JulHendrickson/Module-18-Challenge/assets/81846691/22f3a1f6-3fac-415b-b17c-253d7719afa0)


Once opened users can input the sender, receiver and the amount wanted to transfer. 
Then hit add block to add the transaction to the block.

On the left side any block can be inspected by selecting it from the drop down menu.

![Block_Inspector_code_corrected](https://github.com/JulHendrickson/Module-18-Challenge/assets/81846691/7a5ecbdf-0887-4818-a563-970c6f7872e4)


---
