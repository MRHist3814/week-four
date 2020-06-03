READINGS

* I'm reminded of the diary from an earlier class, and how mining for words and phrases tells us something about the writer.

  * We can 'read' the diary, or the trial, differently. Digital technologies allow for the advancement of arguments.

* Makes me wonder about morality, particularly regarding studies of dead people.

  * Digitization allows for easier access and greater efficiency in research. Scroll through albums of photos rather than dig through physical archives.
  
  * What toll does that play on the morality of the situation? Do historians owe something to the dead, and does digitization change that?

* The confabulaion reading reminds me of the incorrect, yet tempting, approaches to research some people take.

  * Having a hypothesis and working the evidence to fit it, rather than following where the evidence itself leads.

EXCEL

* Followed initial instructions. So far ended up with a sum of P15500:P15503 as 20780. Chart worked fine.

RStudio

* Tried to install the RCurl packages and got an error: "Error in library("RCurl") : there is no package called ‘RCurl’"

  * Was running both lines at once. Fixed that easily enough.
  
* Was having trouble setting my directory to where I wanted it to go. After some internet searches, I found a solution.

* Ran the 'counts' and got a table of results. Made the barchart.

  * My assumption for fixing this would be to do what we did last time with the Texan correspondence. Make clusters.

* Everything seems to have worked as intended.

VOYANT

* Been unable to access voyant-tools.org for two days now. Will move on and return here later.

* Using https://service.sadilar.org/voyant/ as a workaround got me through the process.

  * Corpus ID: 49f48aa297f23faaecb77e664a9f0650
  
* Questions:

  * Is there a trend of negative descriptors applied to colonized peoples, and positive for the colonizers?
  
  * Do terms like 'law, order, peace, civility,' occur when discussing unrest or unease in the colonies?
  
  * Are there splits in opinion between parliamentarians in different parties? Do quotes from either use different terms?
  
  * What progression of language is there as time passes from the 18th into the 19th Century?

* Voyant Example

  * <iframe style='width: 637px; height: 487px;' src='https://service.sadilar.org/voyant/tool/CollocatesGraph/?query=indians&query=natives&mode=corpus&corpus=49f48aa297f23faaecb77e664a9f0650'></iframe>
  
* Not sure I was asking the right questions above. I didn't feel like I knew where to go from there.

ANTCONC

* Used some comparisons similar to 'man' and 'woman' - 'husband' and 'wife,' 'bride' and 'groom,' 'king' and 'queen.'

* I don't know if I downloaded the txt files incorrectly, but all of this is incredibly difficult to read. 

* Patterns are hit and miss. 'King' and 'queen' were difficult to identify. The others were okay.

  * Husbands and grooms are 'strong, angry, stern, loud.' Wives and brides are 'willful, loving, prudent, chaste.'

TOPIC MODELS

* Ran the TMTool and got the results in my output folder.

* Back to work that was more familiar thanks to earlier weeks, this was easier to get through.

* Everything going smoothly until encountering the same 'no package (tm)' error.

  * Adding the two new lines to the script seems to have resolved the problem.
  
* Lacking the topicmodels package, installing it then rerunning also resolved this.

* It took me a while to get used to using the 'Evironment' panel in the upper right to view things as I was working.

* Very relieved when the appropriate visualizations showed up at the end. After many difficulties this week, success!

* I find patterns a lot easier to spot in this type of visualization, rather than the AntConc work.

  * Is there some sort of explosion in romance literature from roughly 1750-1870?
  
  * Why the massive spike in talk of 'life'and 'dreams' in 1730? Possibly related to emergence of Irish independence movements?
  
  * Less talk of God. Possibly as a result of the Enlightenment, common throughout Europe?
