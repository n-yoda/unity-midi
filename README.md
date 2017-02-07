# unity-midi
Play SMF (Standard MIDI File) on Unity.

## Overview
A pure C# MIDI library ([C# Synth Project](https://csharpsynthproject.codeplex.com/))
worked well on Unity with slight modifications.
This repository contains the modified library
and example codes to play an SMF using [OnAudioFilterRead](https://docs.unity3d.com/ScriptReference/MonoBehaviour.OnAudioFilterRead.html).

## Alternative Approach
Using natively supported MIDI APIs will achieve better quality. The following may be useful references.
* [Native Audio Plugin](https://bitbucket.org/Unity-Technologies/nativeaudioplugins/src/a58c1cb0389874593b2a93b41fbb41912f9d670f/NativeCode/Plugin_Synthesizer.cpp)
* [smflite](https://github.com/keijiro/unity-smf-test)

## Licenses for External Resources and Codes
* [C# Synth Project](https://csharpsynthproject.codeplex.com/): The MIT License
* [pathetique-2.mid](http://www.mutopiaproject.org/cgibin/piece-info.cgi?id=295): Public domain
