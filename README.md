# Automating the Boring Stuff with Python

I'm learning Python for a couple reasons. First of all at work I am processing a CSV export from our billing software
that lists all of our customers' addressess and phone numbers. The data is formatted inconsistently. Phone numbers
are missing area codes, addresses aren't standardized (and there are duplicates) and there are other problems.

Our customers will be able to communicate better with our office when we integrate Twilio Flex. This is not a 
straightforward task because I will need to build the database and continue to update it with our billing software,
as it's not a CMS Twilio Flex is designed to integrate with.

We also can implement online sign ups.

As bush league as it sounds the best way to keep the database in sync with our billling software might be to write a
Selenium or Pupeteer script to generate the CSV export, then have some Python Lambda scripts process the data and 
make sure it is up to date. This is not ideal, but neither is exporting a CSV manually when customers need to sign up
online with no notice.

The second reason I am learning Python is to volunteer as a research assistant if I am accepted to UNCA. A friend let
me borrow his data camp subscription and I was introduced to PANDAS and I thought 'wow this is so much better than
anything on Node.js for this purpose'. I was using Node.js as a general purpose language and I see why Python is widely
used.

I don't have statistical knowledge so I don't know if I will be able to be useful right away with Python. But I am 
really looking forward to volunteering and hopefully being useful.