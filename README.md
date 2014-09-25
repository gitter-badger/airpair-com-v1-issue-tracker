<style type="text/css">
	ul.stories li { color:green;list-style-type:circle; }
	ul.stories li.noimplmob { color:#5FB060; }
	ul.stories li.noimpl { color:#CC3D27; }	
	ul.stories li.fail { color:red; }		
	ul.stories li.mobile { list-style-type:disc; }
	ul.stories li.draft { color:#3DBA9D; }
	ol.issues li { font-size:10px;color:gray; }
</style>

#### Key
<ul class="stories">
<li>Completed web only story</li>
<li class="mobile">Complete web + mobile story</li>
<li class="mobile noimplmob">Complet for web, incomplete on mobile</li>
<li class="draft">Feature UX need 2nd pass (suggestions welcome)</li>
<li class="mobile draft">Feature mobile UX need 2nd pass</li>			
<li class="noimpl">Incomplete for web</li>
<li class="noimpl mobile">Incomplete for web and mobile</li>			
<li class="fail">Failing on web</li>						
<li class="fail mobile">Failing on mobile</li>													
</ul>

<p>As of <b><code>Build 1.04</code> Deployed Sep 25</b>. The following stories are in-progress or complete. Test and email feedback to jk@airpair.com.</p>

#### Authentication
<ul class="stories">
<li class="mobile draft">Can login as a new user w google</li>
<li class="mobile draft">Can login as an existing (google) user w google</li>
<li class="mobile draft">Can create email/password login (not matching existing users email)</li>
<li class="mobile draft">Can sign in with existing email/password login</li>
<li class="noimpl">Can link email/passpord login with google login</li>
<li class="noimpl">Can link google login with email/password</li>
<li class="mobile">Can logout</li>	
</ul>

#### Posts
<ul class="stories">
<li class="mobile">Can see recent posts
<ol class="issues">
<li>tags hard-coded</li>					
</ol>
</li>	
<li class="mobile">Can view a post
	<ol class="issues">
		<li class="mobile">disable toc fix for mobile</li>
		<li>toc fix sometimes bleeds into comments</li>					
	</ol>
</li>									
<li class="mobile nfail">Can share a post
	<ol class="issues">
		<li>fb share has not link</li>					
	</ol>
</li>												
<li class="mobile noimpl">Can bookmark a post</li>
<li class="mobile noimplmob">Can view my posts</li>										
<li class="draft">Can create a post</li>													
<li class="draft">Can edit a post</li>									
<li class="draft">Can publish a post (in editor role)
	<ol class="issues">
		<li>Tagging not implemented</li>
		<li>Canonical not implemented</li>
		<li>Editor role not implemented</li>					
	</ol>
</li>		
</ul>

#### Workshops
<ul class="stories">
<li class="mobile draft">Can see upcoming workshops</li>
<li class="mobile draft">Can see historical workshops</li>
<li class="mobile draft">Can view a workshop</li>
<li class="mobile noimpl">Can share a workshop</li>
<li class="mobile draft">Can bookmark a workshop</li>					
<li class="mobile noimpl">Can register to attend a workshop</li>			
</ul>

#### User settings
<ul class="stories">
<li class="noimpl">Can see how to update avatar</li>
<li class="noimpl">Can verify account</li>
<li class="noimpl">Can change account email</li>
<li class="noimpl">Can add, remove and order stack tags</li>
<li class="noimpl">Can order bookmarks</li>
<li class="noimpl">Can remove bookmark</li>
</ul>
