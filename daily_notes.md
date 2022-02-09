15.04.2019
- Arrived.
- Drafted the plan for the 20 weeks at Sydney.
(Viewed a room, liked it and decided to rent it.)


16.04.2019
- anran.wang@data61.csiro.au Email account is working after long waiting and Birgit's huge help.
- Discussed the plan with Rob and Peter, agreed that first reading is not good. Decided to start the encoding from CCSS(Victor's paper) to CCS with respect to strong bisimulation, if it does not work, try encode CCSS into CCSS'(Rob's paper number 135).
- Reading list
	* Rob's paper number 31 chapter 5: the De Simone format.
	* Rob's paper number 135 section 5.3-5.5: CCSS'
- TODO: encoding CCSS to CCS w.r.t. strong bisimulation. If does not work, put CCSS' in the middle and figure out where the problem is.

- Plan for tomorrow:
	* Start the encoding from CCSS to CCS.
	* Get latex and texmaker working.


17.04.2019
- Created a bank account
- Got latex working. Using atom as editor.
- Got the first bit of encoding.
- (done)TODO: finish the first draft of the whole encoding (considering strong bisimulation) and present it to supervisors. (need to rush a bit).


18.04.2019
- Finished the first draft, fixed some problems and presented to my supervisors, got a lot of feed back and the draft needs a lot of fixing.
- TODO:
	* Lemma 1(summarise_signals) is incorrect and incomplete, it needs changing with help of head normal form: (Sigma_i a_i.P_i)^S
	* Does a compositional encoding exist with the fixed lemma 1?
	* Fix the non-compositional encoding.


19.04.2019
- Examined head normal form for CCSS terms, though unfinished.
- Fixed latex label problem.
- Installed steam and DST.
- Plan for tomorrow:
	* Read more head normal form and search for inspirations.
	* Find a counter example. If cannot, disappointed.
	* Proceed with encoding - noncompositional.


20.04.2019
- Looked at HNF. Book: Proof, Language and Interaction. Page 527 section 3.4. (it is more proof for lambda-calculus)
- Compositional encoding seems solid.


23.04.2019
- Presented the newest version of encoding, got a lot of feedback:
	* Recursion and infinity should be considered.
	* Restriction and relabelling can break things.
	* Lacked overview and a lot of background knowledge, also similarity that is provided by other subjects. A great deal of learning is overdue.
- Plan for tomorrow:
	* Write down what was discussed today.
	* Proceed:
		> "The encoding is the unique(to prove) solution of the equation. "
		> A counter example of compositional encoding. (What is compositional?)


24.04.2019
- Sleep deprived because of the neighbour couple was fighting deep into the night.
- Supervisors showed me another neater approach to the proof. Abanden other proofs at the moment.
- Fixed latex font problem (finally).
- Plan for tomorrow:
	* Write down. Include all definitions.
- Reading list:
	* Floyd_Assigning Meanings to Programs.
	* Rob's paper on expressiveness.


26.04.2019
- Writing the definitions.


29.04.2019
- Finished definition writing (for now).
- Sketched semantic proof.
- Read Vaandrager Expressiveness Results for Process Algebras.
	Note: many useful theorems for De-Simone systems.
- Plan for tomorrow:
	* Change definition bisimulation.
	* Read more about CCS, e.g. RvG_Musings section 8.
	* Check out how to borrow books via mycsiro.


30.04.2019
- Changed definition bisimulation.
	Note: correct and valid as encodability criterion.
- Read RvG_Musings.
- Still do not know what process graphs CCS with guarded/unguarded recursion can express.
- Still todo:
	* Read RvG_ACP, mark down definitions.
	* Proof.


01.05.2019 - 03.05.2019
- Reading.


06.05.2019 - 07.05.2019
- Tried constructing an example of separation result for ABC -> CCS(S), needs revising.


08.05.2019 - 09.05.2019
- Reading.


10.05.2019
- Came up with an update of the separation ABC and CCS(S).


12.0502019 - 17.05.2019
- Writing in progress.
- Found flaw in ABC -> CCS separation result proof, solution: strengthen conditions, possibly with barbs.
- Question: definition of reduction relation over broadcast/silent actions. Is it accurate?
- Plan for next week:
	* Revise proof.
	* Move to next encoding / separation result.
	* Continue writing.


20.05.2019 - 24.05.2019
- Rewriting thesis, finished two sections.
- Changed proof for ABC -> CCS.
- Plan for next week:
	* Finish rewriting of section 3, change introduction section.
	* Add priority.


26.05.2019 - 31.05.2019
- Proof scratch: no compositional encoding ABC -> CCS (as it seems), showed it to Rob and Johannes, got a lot of holes poked in the proof.
	Conclusion: the proof is incomplete, needs finishing; however the criterion are in some sense useful.
- Plan:
	* Try to finish the proof if I can.
	* Syntax and semantics of CCS with Priorities.


02.06.2019 - 07.06.2019
- Decided the hole in proof (broadcast -> pure CCS) is unfixable without changing a lot in the definitions, switched to another proof (Versari et all 2008, Phillips 2008).
	Delemma: ditching Gorla's criterion, choose new criterion and have a proof, or stay with classics and have a hard time fixing the proof.
- Plan:
	* Type new proof.
	* New relation: CCSS to ABC?


10.06.2019 - 14.06.2019
- Typed new proof.
- Came up with an encoding CCSS -> CCS_p(local and global priority)
- Plan:
	* Document and write everything.


17.06.2019 - 21.06.2019
- Changed all hand-drawn pictures into computer drawn.
- Added encoding from Broadcast / Signal to Priority, as well as semantics and syntax of CCS with priority (CCS_sg).
- Plan for next week:
	* Revise proof of ABC -> CCS_sg
	* Draft proof of CCSS -> CCS_sg


24.06.2019 - 28.06.2018
- Proof of ABC -> CCS^sg one direction done.
- Rob proposed a proof for "there is no compositional encoding from CCSS to CCS".
- Plan for next week:
	* Try to finish proof ABC -> CCS^sg
	* Start proving CCSS -> CCS^sg
	* Formally write down proof "no compositional encoding CCSS -> CCS"


01.07.2019 - 05.07.2019
- Proof of ABC -> CCS^sg second direction done.
- Finished compulsory learnings at SuccessFactor.
- Still on TODO list:
	* Proof of CCSS -> CCS^sg
	* Formal writing "no compositional encoding CCSS -> CCS"


15.07.2019 - 21.07.2019
- 1. version of revision
- TODO list:
	* Proof ABC -> CCS^sg : relabelling, agent identifier
	* Proof CCSS -> CCS^sg
	* Conclusion section
	* Revision


22.07.2019 - 28.07.2019
- Finished proof ABC -> CCS^sg
- TODO list:
	* Proof CCSS -> CCS^sg
	* Proof no compositional encoding CCSS -> CCS


29.07.2019 - 02.08.2019
- Finished proof CCSS -> CCS
- Revising: section 3.
- TODO list:
	* Revision.

04.08.2019 - 09.08.2019
- Revision of multiple subsections in section 3.
- TODO list:
	* Fix the wrong proof in section 3.5 (ABC -> CCS^sg soundness).
	* Write conclusion section.
	* Continue revising.


11.08.2019 - 16.08.2019
- Conclusion section written.
- Separation result CCS^sg -> CCS.
- Revision in section 3.
- TODO list:
  * Finish and fix proof ABC -> CCS^sg soundness.
	* Revision.


19.08.2019 - 23.08.2019
- Correction proof: no compositional encoding CCSS -> other algebras
- Typo fix and updates according to Rob's notes.
- TODO list:
  * Correction and revision. 
