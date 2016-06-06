# SceneScape Documentation

A new tool for creating dynamic presentations of scenes that tell the
story around events, passions, causes or other themes, with photos,
videos, sounds, and narratives authored by one, or crowd-sourced by
many, scenographers.

## Terminology

* *Scene*

   An assembly of photos, videos, sounds, and text that tell the
   story around some particular person, event, perspective, place
   and/or time.  #MakeAScene

* *SceneScape*

   The 'landscape' of scenes assembled around some theme, by some user
   or set of users as specified by the SceneScape owner, along with
   who is allowed to contribute, contribution requirements and
   limitations, and supported Scene Templates.  Since an arbitrary
   hierarchy of scenes is supported, SceneScapes can also be referred
   to as "super-scenes" or "parent scenes".

* *Sceneshow*

   One or more scenes collected into a continuous presentation,
   analagous to 'slideshow' for just photos.

* *SceneScape Script, aka, Sceneplay*

   The underlying SceneScape XML language that describes the timing and
   relationship structure among the media elements of a given scene,
   or assembly of scenes.

* *SceneScape Script Template*

   A meta script which provides the instructions for constructing
   a scene or list of scenes, and how contributed
   scenes can be created from an uploaded set of photos, videos,
   sounds and text.

* *Crowd- and Friend-sourced SceneScape*

   A SceneScape assembled from scenes by multple contributors,
   e.g., a SceneScape of all scenes (across all users) matching
   hashtag #BostonMarathon2013 or #DinosWedding with the scenescape
   limited to friends of the davesgaze account.

* *Stage*

   The virtual screen & projector responsible for presenting a
   sceneshow.  Built-in stages include the "simple" stage which is
   similar to a slide show for scenes and the "image map" stage for
   navigating among multiple scenes.  

## Example Scripts

You can find example scripts under the "examples" folder.

## SceneScape Script Language

The SceneScape Script language is described in a separate document in 
[markdown](SceneScapeScripts.md) or [pdf](SceneScapeScripts.pdf) format.

## Getting Started

To get started with your own SceneScape:

1. Create a public github repository named "scenescape-xyz", where "xyz" is
   the name of your SceneScape (any length, though shorter tends to be
   better for URLs).

2. Create one or more scene files, optionally in subfolders, with the ".scene"
   suffix.  E.g., "myfamily.scene" and "git push" them into your github
   repository.

3. View your scene at:

   ```http://www.scenescape.com/xyz/myfamily.scene```    

   where "myfamily.scene" is replaced by the relative path to your scene file
   within your SceneScape repository.

(Note that it may take up to 5 minutes for updates to your scenes to
be noticed by our servers.)





