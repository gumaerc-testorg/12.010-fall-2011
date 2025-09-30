---
content_type: page
description: This section provides instructions on using course resources with different
  types of computers.
draft: false
learning_resource_types: []
ocw_type: CourseSection
title: Related Resources
uid: ddefc53c-5c9a-5e34-4407-32ac2e36985b
---
## PC Instructions

If you are familiar with installing software on your PC and know lots about the Windows system you can try to install g77 from the link below. You should read the {{% resource_link "12658087-898c-4d7b-894b-e107f79b99b1" "instructions" %}} first to see if you understand the instructions.

Below is a link to Fortran (g77) for PC:

({{% resource_link "a00a547f-c271-4b95-9c6a-b344d3bf23ec" "http://www.neng.usu.edu/cee/faculty/gurro/Classes/Classes_Fall2002/Fortran77/Fortran77Course.html" %}})

Below are alternative instructions (these require about the same amount of knowledge as the instructions above).

Alternative is to add cygwin to your PC (linux running on PC). Download cygwin from {{% resource_link "a18511a7-2850-4fbd-929d-604ad5184e43" "http://www.redhat.com/services/custom/cygwin/" %}}

Use cygwin\_setup to get gcc, g77 and nedit.

Also needed is

{{% resource_link "a4f3fcde-b024-4114-86b6-524d8f80bb1d" "http://ist.mit.edu/xwin32" %}}

which is the Windows X-window system. (Needed for nedit)

When using X-windows from cygwin you need to add at the terminal prompt

setenv DISPLAY: 0.0

(this allows programs such as nedit and xterm to open windows).

{{% resource_link "d0f80f2b-5a33-4a85-8129-cf2c748e8425" "Installing Fortran" %}} gives instructions for installing gfortran on a PC.

## Intel Mac Instructions

Nedit can be downloaded from   
{{% resource_link "51107262-abf9-4c2b-8754-64562bf1e0f5" "http://sourceforge.net/projects/nedit/files/nedit-executable/5.5/nedit-5.5-MacOSX.tar.gz/download" %}}

gfortran downloaded from {{% resource_link "65edb8fb-8f90-448b-b83d-6c9bae4e8c89" "http://hpc.sourceforge.net" %}} (see links with gfortran in name).

{{% resource_link "f0d7c367-3d11-453f-b234-c62de68f13ea" "Fink commander" %}} is a great utility to install to get lots of linux packages for the Mac.

{{% resource_link "3b63e074-7b6a-4f0a-a82e-31053dbeb8ea" "O'Reilly series of books on programming" %}}

{{% resource_link "f672d3af-32e5-49de-8726-d7aced2762b3" "Fortran Resources and Fortran Compilers for Windows and Linux" %}}