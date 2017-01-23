# humor-humour

I love British comedies and I wanted to see if I could find a way to identify American shows with British senses of humor. Your typical bag of words model probably isn't going to do a great job, apart from finding that words like "bloody" and "London" are trivially more common in British shows, so I decided to use an LSTM recurrent neural net capable of recognizing sequential dependencies between words. 

I collected a training set of episodes of the US and UK versions of "The Office" from http://www.springfieldspringfield.co.uk/ and trained the network to distinguish the shows (ideally the common roots of the shows should help the network focus on the unique British-vs-Americanisms rather than particular subject matter). My trained network was able to successfully identify whether shows like Parks and Rec, Extras, Friends and Monty Python were British or American! With this network, I'm hoping to identify other tastes in shows that are hard to model using individual words alone and make more sophisticated recommendations!

