# TODO

## ✅ Maintain Initial Jump Velocity - COMPLETED

The Character should not be able to alter their jump velocity while "In Air", this breaks the illusion and is very disruptive to the game play because it is not natural. That is not how the physics of jumping works.

**FIXED:** Modified `calculateAirVelocity()` method to preserve the initial jump velocity while in air. The character now only experiences gravity and minimal air resistance, maintaining realistic physics behavior.

**ENHANCED:** Added boost functionality that allows input-based velocity modification while in air when boost is active, providing enhanced mobility for special abilities while maintaining realistic physics for normal jumping.
