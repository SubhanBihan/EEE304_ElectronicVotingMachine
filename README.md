A simplified Electronic Voting Machine (EVM) in Verilog.
Initially, the system verifies a voter's identity by checking their serial number (voter ID). 
Once it confirms that no vote has been previously registered under the same serial number, an authentication signal is generated. 
Subsequently, the voter is allowed to cast their vote for their preferred candidate. These votes are then tallied for each candidate. 
If any of these steps are not completed, the vote is considered invalid and will not be counted. 
This module offers two operational modes: Voting mode, where votes are cast and stored, and Display mode, which shows the vote tallies.
