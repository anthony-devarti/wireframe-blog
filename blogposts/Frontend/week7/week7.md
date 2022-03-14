Technical Article - Blog Post 7
Plotting Pseudocode

	Fiction writers can almost always be divided into two main camps.  They’re often referred to as “plotters” or “pantsers.”  “Pantsers” are called such because, in the most respectful interpretation, they “fly by the seat of their pants.”  Your pantser author will often find themselves surprised by the actions and reactions of their own characters, or even the world as a whole.  Plotters, on the other hand, are called such because they will plot, diagram, outline, define, and research thoroughly.  Usually long before the first bit of prose hits the page. Failing to pre-plan any work will, at best, save a few minutes.  At worst, it will devolve quickly into a series of repetitive corrections that manage to still leave errors on the screen.

	Pseudocoding, much like plot diagrams, serve an irreplaceably important function in the design  and implementation of a project.  If the end user’s experience is the top priority, as it should be, then starting from a top-down perspective allows the creator to construct the entire work around that user, rather than the creator. Pseudocode allows you to have all of your pieces defined and ready before you write your first line of code, meaning that your “characters” are far less likely to surprise you, later.  Disorganization can be disastrous at any step in any project.  The law of conservation of detail[citation] dictates that no detail should be introduced that is not made relevant later.  Declared and unused variables, identical functions with different names, or elements that appear out of order are all signs of lacking pseudocode.

Function chekovsGun ( ){
	if (act1.includes(firearm) && !act2.includes(firearm)){
		return badWriting
	}
}

	Object-Oriented-Programming[citation] demands an even higher level of pseudocoding than functional programming.  Moving pieces, instantiations of previous classes, and a separation of concerns mean things can get very muddy for the pantsers among us very quickly.  Defined, clear objects are like well-written characters.  They have enough information to do everything they need to do, but do not take up more space than they must.  This is nearly possible to achieve if you are simply writing code as you go.  It’s far more likely that a bit of a class’ constructor ends up outside of the constructor block, two methods that could easily be generalized into one, or even that there is a definition of a variable that is defined and forgotten.  Repeated corrections to fix these errors can often have unintended consequences.  If the developer simply moves through, and finds himself surprised by what is needed to accomplish the current goal, then they may end up doing twice as much typing as one who had planned things out and, after all of that extra work, what they are likely to be left with is code that is more verbose, less readable, and less orthogonal than the well-plotted code would likely have been.

	
	Plot development, like code, is very possible to do without a large amount of prior planning and preparatory work.  This approach usually requires a strong mastery of all of the concepts and skills necessary, and will likely take far longer than with a detailed map in hand.  I’m certainly new to coding, but if I were to compare it to something that I have spent far more time with, then I suspect that anyone with enough skill to skip pseudocoding entirely will probably have enough sense not to do so.  For the sake of clarity, I have attached my “pseudocode” for this blog post/ technical article below.

Introduction, overarching concepts of plotter vs pantser dialectic
-define terms, allow for application
-Use overlapping terminology to intimate about possible relations
-establish thesis of the importance of pseudocode

 Segue into code and pseudocode, (relate back to anchor analogy twice throughout)
-pseudocode:code as outlining:fiction
-lack of pseudocode and disorganization
-repetition and DRY concepts, and efficient use of time w/Appeal to doxa (tone)

Object-oriented programming (relate back to anchor once)
-reestablish the opening analogy and extend to OOP
-“defined, clear objects are like well-written characters.  They have enough information to do everything they need to do, but do not take up more space than they must.”
-spacial nature of OOP requires even more prior planning than functional programming.

Conclusion 
	-last relation to anchor(brief, 1-2 sentences)
	-pseudocode’s role in OOP
	-confirm necessity of pseudocode through negative example
	-direct to this outline as example