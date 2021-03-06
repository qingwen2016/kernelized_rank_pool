Implementation of Kernelized Rank Pooling variants. If you use this code,
please cite our paper:

 <b><a href="http://users.cecs.anu.edu.au/~cherian/papers/krpfs-cvpr18.pdf">Non-Linear Temporal Subspace Representations for Activity Recognition, <br>A. Cherian, S. Sra, S. Gould, and R. Hartley, CVPR 2018. </a></b>
 
 This code implements:
 1. Basic Kernelized Rank Pooling (BKRP) 
 2. Improved Basic Kernelized Rank Pooling (IBKRP)
 3. Kernelized Rank Pooling with Feature Subspaces (KRP-FS) 
 4. Rank Pooling (Video Darwin) 
 5. Linear (Video Darwin, but implemented using a linear kernel) 

<br>
 For bugs and comments, email Anoop Cherian at anoop.cherian@gmail.com. 
 Copyright (c) 2018, Anoop Cherian. All rights reserved.
 
 <br><br>
 Note: The following code shows a demo implementation and usage of KRP schemes
 on the JHMDB dataset split 1. JHMDB uses VGG-16 fc6 features (available
 in the bundle). Data for HMDB dataset ResNet-152 two stream features are
 available separately.

<br><br>
<b>Dependencies:</b><br>
 The code has the following dependencies which you have to download separately and unzip to appropriate folders. 
 1. LibLinear version 2: 
 2. ManOpt Package
 3. LibSVM version 3.14
 <br>
 All the above are available for download from http://users.cecs.anu.edu.au/~cherian/code/krp_fs.zip.
 
 <br><br>
 A link to <b>HMDB dataset ResNet-152 features</b> for RGB and Flow is available at http://users.cecs.anu.edu.au/~cherian/
 
 <br><br>
 <b>How to run the code?</b> <br>
 Run demo_krp() in Matlab to see the usage. The code runs KRP on JHMDB dataset split 1. Tested on Matlab 2018.

<br><br>
DISCLAIMER<br>
 Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:<br>
 1. Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer. <br>
 2. Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution. <br>
 3. Neither the name of the copyright holder nor the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission.<br>
 THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A
 PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, 
 INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF 
 SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY 
 OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT 
 OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
