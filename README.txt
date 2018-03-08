/*~ README.txt
.---------------------------------------------------------------------------.
|  Software: Esimple Studios Unity3D Anaglyph-izer Pack                     |
|   Version: 1.3                                                            |
|   Compatibility: Works on Unity3D 17.2 or higher.                         |
|   Contact: info(at) www.esimple.it                                        |
| ------------------------------------------------------------------------- |
|     Admin: Francesco Gallorini (project administrator)                    |
|	  Developers: Juan Alvarez, Francesco Tozzi, Francesco Marcantoni   |
|     Packaging: Gabriele Maidecchi                                         |
| Copyright (c) 2010, Esimple Studios All Rights Reserved.                  |
| Based on the original concept by: aNTeNNa trEE (Unity Demo Team)          |
|                                   Monark                                  |
| ------------------------------------------------------------------------- |
|   License: Distributed under the GNU GENERAL PUBLIC LICENSE (GPL)         |
|            http://www.gnu.org/licenses/gpl.html                           |
| This program is distributed in the hope that it will be useful - WITHOUT  |
| ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or     |
| FITNESS FOR A PARTICULAR PURPOSE.                                         |
'---------------------------------------------------------------------------'
*/


Everything started from this forum post: http://forum.unity3d.com/viewtopic.php?t=12525&highlight=anaglyph

We took the script posted by aNTeNNa trEE of the Unity Demo Team.
We added the modification posted by Monark implementing the projection matrix method, to simplify vision for the eyes.
Monark also posted a modified shader from the original one, which we included by default.

Then, we cooked all our modifications, and we finally released it under GPL for everyone to enjoy.

If you are even remotely like us, you'll spend hours firing at stuff in the bootcamp demo like idiots.

WHAT IS NEW (1.3)

- The project was updated to the version "2017.2.2f1"
- The code was corrected and updated. 
- Update a "Use Projection Matrix" flag to optimize the focal distance based on the camera is Field of View
- The js code was eliminated for future obsolescence of javascrit in Unity.
- The demo was corrected to support the new Unity17 "Shaders"
- changed the folder structure to be more "Unity-friendly"
- A 3D glasses template is added

INSTALLATION

ONLY FOR 2.6.1: replace the shader in the package with the correct version in the source/Shaders/2.6.1 folder

1) Link the AnaglyphizerJ.Js (Javascript) or AnaglyphizerC.Cs (C#) to the camera. Or Select Camera and Open Component -> Anaglyphizer -> Anaglyphizer(Cs or Js)
2) Link your material or one of those included in the prefab folder to the script

Inspector variables to change script parameters:

Use Projection Matrix -> Flag
Improve correct lens calculation based on Field Of View parameter