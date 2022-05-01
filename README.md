# Module-Challenge-18: Pychain Ledger
## Step 1: Create a Record Data Class
### We first created a record data class with a sender, receiver, and amount as follows:
 @dataclass
 
 class Record:
    
    sender: str
   
    receiver: str
   
    amount: float
    
## Step 2: Modify the Existing Block Data Class to Store Record Data
### We rename 'data' to 'record' and set it to the Record datatype with record: Record

## Step 3: Add Relevant User Inputs to the Streamlit Interface
### We first get rid of the input_data variable (I just #'d it in the code). Next, for sender, receiver, and amount variables, they are assigned to st.text_input() with the accompanying 'Sender', 'Receiver', or 'Amount' within text_input(). Next, we need to update new_block to incorporate the sender, receiver, and amount, which is done by adding the code:
### record=Record(sender, receiver, amount).

## Step 4: Test the Pychain Ledger by Storing Records

![sl-page](https://user-images.githubusercontent.com/95319421/166154496-34031079-ae20-41e3-b8ba-db564c4d67c5.PNG)


![validate](https://user-images.githubusercontent.com/95319421/166154472-c015dadb-f6dc-43ec-bd07-dea23b627ec4.PNG)
