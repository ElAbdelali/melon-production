# Melon Production

To: jrdev48@ubermelon.co <Junior Developer #48>
From: mel@ubermelon.co <Mel M>
Subject: Winter Squashes Are Coming!!!!!!

Hey!

I'm writing a note to you about some exciting changes coming up!

Our CEO has decided to confront Squysh head on, and so we're going to be
introducing our new line of Ubermelon Winter Squashes in just 10 days.

As you know, our CEO has invested billions of VC money in our robotic
production and order fulfillment delivery chain.

It's all managed by the code in shipping_procedure.py.

shipping_procedure.py works great with melons (e.g. when processing the
standing_orders1.log file) -- but can you check to see what we need to
change so that it can handle squashes?

The file standing_orders2.log has an order for squashes.

Before shipping, all melons are evaluated by the InspectorBot for
quality standards. The winter squashes are being rejected because they
are not green like the watermelons are.

We've contacted the company that made the InspectorBot, but they've
informed us it will cost millions of dollars in consulting fees to
upgrade the robot's software to handle two types of melons.

As a result, the CEO has decided it would be best to paint the Winter
Squash green to match the watermelons.

Please add a Squash melon class to melons.py. Give Squash class a
special prep procedure to paint the squashes correctly. To invoke the
paint bot that's already been installed at the factory, you can call
the following function:

     robots.painterbot.paint(self)

Thanks for your help,
Mel
Team Lead

P.S. Don't change anything about the robots.py file. You should be able
to make any necessary changes in melons.py.

# To Do
1. Add a Squash class to melons.py to handle winter squashes. (We’re considering squashes to be a type of melon.)

2. Add a method to your Squash class that handles the prep plus painting of squashes.

    Hint: try processing the standing_orders2 log with our shipping procedure to see what happens to squashes currently.

    Don’t get bogged down in robots.py. You don’t need to do anything with that file.       