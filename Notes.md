/* tried to use #toggle to
target <p> and <btn> of that #id,
but it doesn't work! */

/* ' .heading p ' has a level of (11)
and #toggle has a level of (100) */

/* BUT because #toggle div is nested inside .heading div,
the <p> tag inside #toggle is targeted
by both declaration and has a level of (111),
and thus is higher than #toggle by itself.

! Add p to #toggle declaration */

/*// #toggle */

#toggle p {
	color: hsl(230, 22%, 74%);
	display: inline;
	padding: 0;
	margin: 0;
}

