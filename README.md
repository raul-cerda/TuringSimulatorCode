# TuringSimulatorCode
For HMWK 2

//Code for language A
name: A
init: q1
accept: qAccept

q1,0

q1,0,>

q1,1
q2,1,>

q2,0
q3,0,>

q2,1
q2,1,>

q3,0
q1,0,>

q3,1
q4,1,>

q4,0
q5,0,>

q4,1
q2,1,>

q5,0
q6,0,>

q5,1
q4,1,>

q6,0
q7,0,>

q6,1
q2,1,>

q7,0
q6,0,>

q7,1
q2,1,>

q5,_
qAccept,_,-

q7,_
qAccept,_,-


//Code for language B
name: B
init: q1
accept: qAccept

q1,0
q2,_,>

q1,_
qAccept,_,-

q2,0
q2,0,>

q2,1
q2,1,>

q2,_
q3,_,<

q3,1
q4,_,<

q4,0
q4,0,<

q4,1
q4,1,<

q4,_
q1,_,>
