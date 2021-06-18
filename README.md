# PowerAutoPwn
Testing Microsoft Power Automate as an offensive security tool.

Just like usual, I was sitting around on the computer minding my own business when suddenly I noticed a tool called "Microsoft Power Automate" on my computer.  It must come bundled with Office 365, which I had recently purchased.
I am a huge fan of lowcode/nocode because I think it makes coding more accessible to people.  In my old life, I was a certified Dynamics 365 consultant who spent a lot of time watching the Power Platform evolve into what it is today.  This tool is super impressive and the teams at Microsoft who pulled this off should be really proud of themselves.  Now, unfortunately, I will make it do things it was never designed for :)

![gmFxRAhq6y](https://user-images.githubusercontent.com/2859638/122591572-c0644c80-d028-11eb-8321-d7f78b960841.gif)

To use any of the scripts I put here, just copy the text and paste it into your Power Automate "flow".  After pasting, you should get a nice visual representation of what the code does.

Good luck, and be careful.  A lot of the research I do is kind of a fringe area so use common sense before you run anything here.

Some immediate improvements that can be made to the s3 script in its current form:

1) Do more validation with errors
2) log errors to a database or file
3) remove error entries from the CSV
4) Have file paths/file names/etc not be hardcoded.

