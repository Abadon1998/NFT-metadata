# NFT-metadata

For this example I used Moonbears
There are several steps:

1)Get the contract address (0x3B8420eB6EF77Bc25025b32D8205cde2683F979E)
2)Read the contract and query the tokenURL section, grab the relavent url leaving out the token id.
- e.g. https://moonbears.mypinata.cloud/ipfs/QmXMJ8Eysnx9Qwk1Wozv7UbGKvwr7r7sP2oUg5gwEd3z9R/
- If this URL is a IPFS URL then only copy the end sequence e.g. QmXMJ8Eysnx9Qwk1Wozv7UbGKvwr7r7sP2oUg5gwEd3z9R
3)Enter the supply and the starting ID of the first token
4)If using a base URL (unique) change the input of the **test_url** function to base_url, if IPFS URL then use ipfs_url
5)Do the same for the **scrape_metadata** function in the cell below.
6)Ensure the correct email address and password is selected and the relavent recipient is inputed.
7)Run all cells and check email address

There is LOTS that need tweaking in here and emailing someone every time is not very efficient so other means of communication are needed.
The run is pretty quick on my 100mb/s internet, netting a total time of ~45 secs, but on server speeds this would be much faster.
There is a lot to figure out but i think its a pretty good frame work/idea to work from.

Anyway give it a try and let me know what you think.
