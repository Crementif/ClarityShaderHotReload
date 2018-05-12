============================ Clarity Preview Tool ============================
What is this?
 - A tool that'll let you edit the Clarity graphic pack in real time. Meant
   to make things like creating your own presets much easier.

So how do I install it?
 - Move the opengl32.dll into your Cemu directory. Also, Clarity must already
   be downloaded and enabled. You MUST use separable shaders for this to work!
   Convential shaders don't work. That's it!

So I've installed it, what now?
 - Launch (and enable Clarity's graphic pack for) BotW. If everything is
   done correctly, it should open the shader text file from your Clarity pack.
   Now you're free to make any change to your liking. This tool will show any
   changes you make, live. If the screen gets black it's because the shader
   can't compile. Basically, you've got an error in your shader now.

I've created my own preset! Is there something else?
 - Yeah. You can (at any point) remove the opengl32.dll from your folder to
   deinstall this whole tool. It's recommended to do this after you are done.

Getting some issues?
 - Well, that's to be expected with this very hacky solution. Try reading your
   "ClarityPreviewTool.log" and see if there's any errors.

Any other plans?
 - No, I don't plan on updating or open sourcing this. However, it's based
   on https://github.com/glampert/GLProxy, license:

The MIT License (MIT)

Copyright (c) 2015 Guilherme Lampert

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.