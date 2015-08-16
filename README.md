Delete:
	d	delete command
	x	delete single character
	D	delete to end of line
	X	delete backwards single character

Find:
	f	find character after cursor in current line
	F	backwards version of "f"
	t	same as "f" but cursor moves to just before found character	
	T	backwards version of "t"
	
	
Replace:
	r	replace single character at cursor	
	R	replace mode - replaces through end of current line, then inserts	
	c	change command
	s	substitute single character with new text
	C	change to end of line
	S	substitute entire line - deletes line, enters insertion mode	
	viwp	replace word with content of clipboard

Insert:
	a	enter insertion mode after current character
	i	enter insertion mode before current character	
	A	enter insertion mode after end of line	
	I	enter insertion mode before first non-whitespace character
	o	open line below and enter insertion mode

Move:	
	b	back word
	e	end of word
	E	move to end of Word (end of non whitespace)
	
	h	move left one character
	j	move down one line
	k	move up one line
	l	move right one character
	w	move foreward one word
	W	foreward Word
	
	L	goto last line on screen
	M	goto middle line on screen
	
	{	move to previous blank-line separated section	
	}	move to next blank-line separated section	
	$	move to end of line
	
	|	move to column zero
	-	move to first non-whitespace of previous line
	G	goto line number prefixed, or goto end if none
	gg	move to first line of file
	H	home cursor - goto first line on screen
	
	0	move to column zero
	^	move to first non-whitespace character of line
	%	match nearest [],(),{} on line, to its match (same line or others)

Copy/Paste:
	y	yank command
	Y	yank entire line
	p	put buffer after cursor
	P	put buffer before cursor

Extra:
	J	join current line with next line
	<	unindent command	
	>	indent command
	u	undo
	B	move back one Word

======





g	UNBOUND
m	mark current line and position	
n	repeat last search
q	UNBOUND
v	UNBOUND
z	position current line	
K	UNBOUND
N	repeat last search, but in opposite direction of original search
O	open line above and enter insertion mode	
Q	leave visual mode (go into "ex" mode)
U	restores line to state when cursor was moved into it
V	UNBOUND
Z	first half of quick save-and-exit	
1-9	numeric precursor to other commands	
 	(SPACE) move right one character
!	shell command filter	
@	vi eval	
#	UNBOUND
&	repeat last ex substitution (":s ...") not including modifiers
*	UNBOUND
(	move to previous sentence
)	move to next sentence
\	UNBOUND

_	similar to "^" but uses numeric prefix oddly
=	UNBOUND
+	move to first non-whitespace of next line
[	move to previous "{...}" section	
]	move to next "{...}" section	

;	repeat last "f", "F", "t", or "T" command
'	move to marked line, first non-whitespace	
`	move to marked line, memorized column	
:	ex-submode	
"	access numbered buffer; load or access lettered buffer	
~	reverse case of current character and move cursor forward
,	reverse direction of last "f", "F", "t", or "T" command
.	repeat last text-changing command
/	search forward	

?	search backward	
^A	UNBOUND
^B	back (up) one screen
^C	UNBOUND
^D	down half screen
^E	scroll text up (cursor doesn't move unless it has to)
^F	foreward (down) one screen
^G	show status
^H	backspace
^I	(TAB) UNBOUND
^J	line down
^K	UNBOUND
^L	refresh screen
^M	(CR) move to first non-whitespace of next line
^N	move down one line
^O	UNBOUND
^P	move up one line
^Q	XON
^R	does nothing (variants: redraw; multiple-redo)
^S	XOFF
^T	go to the file/code you were editing before the last tag jump
^U	up half screen
^V	UNBOUND
^W	UNBOUND
^X	UNBOUND
^Y	scroll text down (cursor doesn't move unless it has to)
^Z	suspend program
^[	(ESC) cancel started command; otherwise UNBOUND
^\	leave visual mode (go into "ex" mode)
^]	use word at cursor to lookup function in tags file, edit that file/code
^^	switch file buffers
^_	UNBOUND
^?	(DELETE) UNBOUND

http://hea-www.harvard.edu/~fine/Tech/vi.html
