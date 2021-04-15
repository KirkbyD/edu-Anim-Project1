INFO6022 - Animation
Project #1: Make it work!
(Decoupling and External Configuration for our existing code base!)

Submission by Dylan Kirkby, Brian Cowan, Ivan Parkhomenko

Created in Visual Studio 2019 Community Edition
Solution runs on Platforms and configurations.

Simply open in visual studio and build, it should all be configured with the correct dependencies.

Relevant Controls:
Keyboard:
	W		Walk Forward
	S		Walk Backward
	Q		Strafe Left
	E		Strafe Right
	Space		Jump
	+Shift		Modifies above keys to do things faster (excpt turning)s
	A		Turn Left
	D		Turn Right
	R		Reset to regular idle
	Cursor left/right
			Change Selected Animated Entity.

Mouse:
	Left		Combat Mode / Punch
	Right		Face character camera's direction
	Move		Rotate Camera
	Wheel Up	Zoom Out (Camera starts at max distance)
	Wheel Down	Zoom In

External files can be found in:
	Entities	$(SolutionDir)AmethystEngine\data\config\complex\Entities.json

Uploaded using the Zombie shown at end of video, much easier to test with just elve's though.
New items for project:
	cAnimationManager
	cAnimationComponient
	cTransformComponent

also refer to 
	cPhysicsManager Update()
	cFileManager BuildEntities()

Short and sweet readme since I have to hand this in ASAP!