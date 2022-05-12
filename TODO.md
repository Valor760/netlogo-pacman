TODO:
	-[ ] In state 3 make so that pacman would go to the power pill
		 and stay near it while ghosts are not near
		-[ ] Use manhattan metrics
	-[ ] Implement states
		-[ ]	State where pacman eats ghosts
	-[ ] Figure out what to do with blank spaces on the map?
		-[ ] Maybe restrict pacman to go there?
		-[ ] Or better handle it, so that he wouldn't stuck and goes straight to pellet
	-[ ] Add a lot of randomization
	-[x] Remake the calculation method of distance from the pill to the ghosts in state 3.
		-[x] The problem is that calculations are based on pacman distance to the pill and ghost.
			Need to ask directly from pill.