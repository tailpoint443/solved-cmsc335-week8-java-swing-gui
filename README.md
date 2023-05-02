Download Link: https://assignmentchef.com/product/solved-cmsc335-week8-java-swing-gui
<br>
In this project you will construct a Java Swing GUI that uses event handlers, listeners and incorporates Java’s concurrency functionality and the use of threads. The following book may be useful to help you become comfortable with Thread processes.

<a href="https://learning.oreilly.com/library/view/java-7-concurrency/9781849687881/index.html">https://learning.oreilly.com/library/view/java</a><a href="https://learning.oreilly.com/library/view/java-7-concurrency/9781849687881/index.html">–</a><a href="https://learning.oreilly.com/library/view/java-7-concurrency/9781849687881/index.html">7</a><a href="https://learning.oreilly.com/library/view/java-7-concurrency/9781849687881/index.html">–</a><a href="https://learning.oreilly.com/library/view/java-7-concurrency/9781849687881/index.html">concurrency/9781849687881/index.html</a>

You should focus on the first 4 chapters.

If you have previously signed up for the Safari account you don’t need to sign-up again. Just use this link: <a href="https://learning.oreilly.com/accounts/login/?next=/library/view/temporary-access/">https://learning.oreilly.com/accounts/login/?next=/library/view/temporary</a><a href="https://learning.oreilly.com/accounts/login/?next=/library/view/temporary-access/">–</a><a href="https://learning.oreilly.com/accounts/login/?next=/library/view/temporary-access/">access/</a>

If you have not previously requested a Safari account follow the details on this page to sign-up for your Safari Account: <a href="https://libguides.umuc.edu/safari">https://libguides.umuc.edu/safari</a>

You’ll need to sign in using your UMGC student email account. Once you sign in, you’ll have immediate access to the content, and you’ll shortly receive an e-mail from Safari prompting you to set up a password and complete your account creation (recommended).

Students: Your UMUC e-mail account is your username + @student.umuc.edu (example: <u><a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="e58d968a898ad7a596919081808b91cb90889086cb808190">[email protected]</a>)</u>.

<strong>In addition, a zip file is included that includes several Oracle Java files that use different types of Swing components as well as threads.  I recommend going through the reading and the examples to become familiar before attempting the final project. </strong>

<strong>Assignment Details </strong>

As a new engineer for a traffic congestion mitigation company, you have been tasked with developing a Java Swing GUI that displays time, traffic signals and other information for traffic analysts. The final GUI design is up to you but should include viewing ports/panels to display the following components of the simulation:

<ol>

 <li>Current time stamps in 1 second intervals</li>

 <li>Real-time Traffic light display for three major intersections</li>

 <li>X, Y positions and speed of up to 3 cars as they traverse each of the 3 intersections</li>

</ol>




Some of the details of the simulation are up to you but the following guidelines will set the guardrails:

<ol>

 <li>The components listed above should run in separate threads.</li>

 <li>Loop through the simulation with button(s) providing the ability to start, pause, stop and continue the simulation.</li>

 <li>You will need to use basic distance formulas such as distance = Speed * time. Be sure to be consistent and define your units of measure (e.g. mile/hour, versus km/hour)</li>

 <li>Assume a straight distance between each traffic light of 1000 meters.</li>

 <li>Since you are traveling a straight line, you can assume Y = 0 for your X,Y positions.</li>

 <li>Provide the ability to add more cars and intersections to the simulation through the GUI.</li>

 <li>Don’t worry about physics. Assume cars will stop on a dime for red lights, and continue through yellow lights and green lights.</li>

</ol>

Document all assumptions and limitations of your simulation