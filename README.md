# Zed-Test (Tao)
For recording, exporting, and converting

Three application:
1. Recording App folder includes released recording app, I upload three typical exposure time (20%, 30%, 50%), all of them is under VGA resolution and 100FPS,  you can use them directly, the exe will create the recording file as a .SVO
For using the exe, should using CMD, the paramater is like:  .../.../ZED_SVO_Recording Result.svo
                                                            exe path    exe name       result file name (any name)        
2. export-video-only folder includes the exe which can convert .svo to .avi Just put the svo file (should change the file name to test.svo) into the same folder with exe, then run the exe (no necessary to use CMD), then will create the test.avi 
3. export folder includes the exe which can convert .svo both to avi. and .png, the same using with 2. (Attention, also need the name test.svo)


Addition:
1: In 2 and 3, the .exe is in the bulid/release/, you can change the code to rebulid them. But for this function, I think no need to rebulid them.

2. The recording code is in recording folder, you can change the camera resolution, FPS, exposure time in the code, and rebulid it.

3: Actually, sometimes there is unknown reason to error building, and when it occurs error, never successfully rebuild again. As this reason, I separate some typical exposure time .exes in Recording App folder, if you can not rebulid again, just use that. 

4: I also uploaded the original codes as the zip, if the solution is broken, and can't successfully rebuild again (mentioned 3), you can use cmake to rebulid the original code, and just copy the broken solution's code to new code, it should be working.
