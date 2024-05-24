# HAOS-GPT-Theatre
Human-readable form of the inputs to ChatGPT to generate Home Assistant automations

This is an approach of documenting and describing my theatre to ChatGPT3.5 providing useful details where needed but generally staying conceptual rather than directive.

I created a text file where I describe the room, the objects in it, what the room's used for, what existing devices and entity names, if any, are already in HA, some rules, and then what I want to automate.  
I give it some tips on how I want them structured, and how I want it to present them to me (I don't want a single automation, and I don't want it to dump all of them out to me at once.  
I want to see the first one, iterate with it until I'm happy, then continue.).  I also want it to explain back to me what it thinks it understands.

The general idea is that rather than my getting into the technical aspects of the automation immediately, I keep a few steps back and tell it what I want to be able to do, in normal conversational methods, using generalisations. So if I tell it I have a server that I don't want it to get too hot, and a couch, and that the house's air conditioning feeds into the room but I use a separate fan to bring in fresh air, my hope is that it will grasp these concepts and create solutions and automations that utilise this understanding.

Then I paste it into chatgpt.  It reiterates it's understanding of the situation and what I want to be able to do, then it presents the first automation and explains what it is doing.  And we go from there.

Then if I come back to things a day or week later, I simply paste the text file back into chatgpt and tell it where we're up to, and we continue.

It seems to work well - it describes the environment and produces suggestions that make sense.  For example it will understand people don't want the room too warm; that there's no point cooling an empty room; that the lights shouldn't all go (back) on if a second person enters a room where someone is already in it watching a video. 

**
