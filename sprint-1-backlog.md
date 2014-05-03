# SPRINT 1 REPORT

# Team Andromedus

Alexis Hoshino, Eric Tian, HQ Pham-Nguyen, Kathleen Enverga

### SPRINT 1 BACKLOG

### Stories
+ Stories Table
+ Story Model
+ Stories Controller
+ Story View: create.blade.php, index.blade.php, edit.blade.php, show.blade.php

### Photos
+ Photos Table
+ Photos Model
+ Photos View: create.blade.php, index.blade.php, edit.blade.php, show.blade.php, remove.blade.php
+ PhotosController

### Invitations
+ Invitation Model
+ InvitationsController
+ Invitations View: index.blade.php
+ Invitations Table

### Collaborators
+ User_Memorial Join Table
+ CollaboratorsController
+ Collaborators View, add.blade.php, index.blade.php, remove.blade.php

### Videos
+ Videos Table
+ Videos Model
+ Videos Controller
+ Videos View: create.blade.php, index.blade.php, edit.blade.php, show.blade.php



(SPRINT 1 REPORT):
## Initial Tasks
	+ Kathleen: In charge of implementing photos feature
	+ Alexis: In co-charge of Collaborators & Invitations (with Grace)
## Completed
	+ Photos:
+ Delete function for photos work
+ Redirecting from memorial view to photos page link works 
+ Included file upload function
+ Invites
	+ Send an Invite
	+ Receive an Invite (Accept or Reject)
	+ View received invites
	+ Hide Invitations button when no pending invites have been received.
+ Collaborators
	+ Join user to a memorial once the invitation is accepted
+ Remove the join table row and invite row for that pair if user leaves the memorial
+View current and pending collaborators
+ Remove collaborator if memorial admin
## Not Completed
+ Photos:
		+ Cannot successfully upload a photo
		+ No gallery to display uploaded photos
	+Leave Group (Collaborators)
		+ Functional until recent UI update was pushed. In need of bug fix.
