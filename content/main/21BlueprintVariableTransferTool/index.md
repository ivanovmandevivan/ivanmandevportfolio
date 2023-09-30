+++
weight = 1
image = "BlueprintVariableTool.png"
date = "2023-09-30"
title = "Blueprint Transfer Tool"
type = "gallery"
+++

{{< youtube 1cQQz_yMRDg >}}

---

**Title**: Blueprint Transfer Tool\
**Genre**: Tools

Sometimes, copying and pasting variables between blueprints can be a very manual process and Unreal Engine does not allow you to do it in a comfortable manner, thus why the creation of this tool.

This tool essentially allows you to copy variables from one source blueprint to one/multiple target blueprint(s).

This was done entirely using the Unreal Engine API / pipeline, digging down into concepts such as:

- Slate
- Widgets
- Unreal Blueprint Editor Utility Library.
- C++

With this project I thoroughly learned how to build interfaces with Slate, explored the inner workings of how blueprints work, where the variables are stored and multiple helper functions to be able to rename, duplicate, move variables between different blueprints as well as how to attach commands, new windows to the current engine editor whilst also having in mind how to solve a very painful task, which can be as simple as allowing you to bulk copy variables in a blueprint.