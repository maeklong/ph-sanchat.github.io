<h1>Authenticator Lifecycle Requirements<h1>
<table>
<tr>
<th width="25%">Preconditions</th>
<th width="15%">Inputs</th>
<th width="30%">Actions</th>
<th width="30%">Expectd</th>
</tr>
<tr>
<td width="25%">Correct username and password</td>
<td width="15%">
Username<br>
password
</td>
<td width="30%">
1.Open page login<br>
2.Add username <user><br>
3.Add password <1234><br>
4.click button login
</td>
<td width="30%">
1. User can log in<br>
2. Information page display system<br>
3. Message system "Welcome to login"
</td>
</tr>
<tr>
<td width="25%">Incorrect password</td>
<td width="15%">
Username<br>
password
</td>
<td width="30%">
1.Open page login<br>
2.Add username <user><br>
3.Add password <5555><br>
4.click button login
</td>
<td width="30%">
1. User cannot log in<br>
2. Message system "Could not log in" please check username and password”
</td>
</tr>
<tr>
<td width="25%">Incorrect</td>
<td width="15%">
Username<br>
password
</td>
<td width="30%">
1.Open page login<br>
2. click button login
</td>
<td width="30%">
1. User cannot log in<br>
2. Message system "Could not log in" please check username and password”
</td>
</tr></table>

<h2>Team Author</h2>
<ul> 
<li>Wasupol Chaisangasilp</li>
<li>Sanchat Phaisit</li>
</ul>