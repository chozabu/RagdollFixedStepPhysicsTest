# ragdolltimetest

for use with UE4 branch: https://github.com/chozabu/UnrealEngine/tree/4.22-Physics

This is a test project for UE4 fixed time-stepping, with added interpolation on skeletal meshs - based on 0lentos work

The primary core concept of fixed timesteps in unreal engine is to provide deterministic physics (for physics puzzle games, vehicles, etc)  
Another key goal is preventing simulation instability when altering TimeDilation (Changing in steps > 0.03 can be problematic)

Check ProjectSettings->engine->physics->framerate to configure settings
