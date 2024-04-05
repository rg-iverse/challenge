# Challenge

Build a crowd funding SC on MultiverseX (MVX) that will have the following functionalities:
1. An admin account will be able to create numerous crowdfunding campaigns for various projects. A project is defined by a certain account address
2. A crowdfunding campaign must reach a minimum token amount raised. If the minimum amount is not reached, the tokens will be sent back to the senders
3. A crowdfunding campaign must adhere to a deadline, which is determined by the administrator. Once the deadline is reached, the tokens are to be transferred to the project wallet. (build a cron job that checks if the project is ended)