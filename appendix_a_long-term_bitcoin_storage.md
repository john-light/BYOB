# Appendix A: Long-Term Bitcoin Storage

##Checklist

☐  Generate bitcoin private keys on an offline computer.
 * Use a computer that will never again be attached to the Internet, or
 * Use Linux LiveCD or LiveUSB, a temporary operating system for generating private keys.[^34]  
 * Use diceware or some other provably random method of generating entropy when creating your private keys.[^35]  
 
☐ Backup bitcoin private keys.
 * Ensure that your loved ones will have a way of accessing the keys should anything happen to you, otherwise your bitcoin will be irretrievable.
If the private keys being backed up are used to create a multisignature account, store each key backup in a separate physical location so that they are harder for an attacker to recombine.
		☐ Paper
		☐ USB
		☐ CD-R  

☐  Create a 2-of-3 multisignature account.
 * 2-of-3 ensures that if one key is lost, the two remaining keys can still be used to recover funds and move them to a new, uncompromised 2-of-3 account.  
 * You can also generate a 3-of-5 account, which offers even more redundancy.  

☐  Use the public address of the multisignature account to receive bitcoin.  
 * A multisignature account address will always start with a 3.  

☐  Practice receiving and sending very small fractions of a bitcoin before trying to store large amounts.  
```
☐  Generate an unsigned transaction using your hot wallet. 
☐  Transfer unsigned transaction data to each of the computers 
   that the cold private keys for the multisignature account are 
   stored on.  
☐  Sign the transaction using the cold private keys for the
   multisignature account.  
☐  Combine the signatures together properly to produce a valid 
   transaction.
   ☐  Transfer the signed transaction to an online machine and 
	  broadcast it to the bitcoin network.
      * If bitcoin are sent from the address, success! If not, 
        re-trace steps and try again.```

[^34] https://bitcoinpaperwallet.com/ubuntu-linux-live-bootable-cd/  
[^35] http://www.contravex.com/2014/03/14/on-making-high-entropy-bitcoin-paper-wallets/  