openfeathercoinatm
==============

Open Feathercoin ATM -- The worlds first completely open-source Feathercoin ATM, based on John Mayo Smith's OpenBitcoinATM.

See the OpenBitcoinATM in action here: http://youtu.be/A4KvAgJx4GU

This will be a starting point for a FTC implementation.

The initial release will have cosmetic changes which will port the functionality but use FTC artwork and wallet QR codes.

The subsequent functionality will aim to include support for multiple banknotes, ideally coin support, realtime exchange rates using network connectivity etc.

For now, the code should dispense private keys when a 1 pound coin is inserted into the coin acceptor, this will work with any coin or note/bill acceptor which outputs 4 pulses.
For this to work, a series of private key QR codes need to be generated with 4FTC (or whatever number you want to sell for £1!) and encoded as byte arrays. These need to be uploaded to the SD card.

I am still working on the logo to print above the QR code and tidying this up. 

I strongly recommend that this is run with the test flag set to print the same QR code each time until you are happy the code works.

Please give me any feedback you might have.
