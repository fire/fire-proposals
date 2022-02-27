# Elixir desktop tool to batch execute Godot

- Status: proposed <!-- draft | rejected | accepted | deprecated | superseded by -->
- Deciders: fire,
- Tags: fire,

## Context and Problem Statement

Want to automate my Godot workflows to auto rig and auto animate a character.

## Describe the proposed option and how it helps to overcome the problem or limitation

Use my existing tooling to pipeline execute Blender workflows.

## Describe how your proposal will work, with code, pseudo-code, mock-ups, or diagrams

1. everything is airgapped
1. execute desktop elixir app
2. create sqlite database
3. rest queue jobs from s3
4. execute pipeline using pull
5. push to s3

## Positive Consequences <!-- optional -->

- Experiment seed

## Negative Consequences <!-- optional -->

- ???

## Option graveyard: <!-- same as above -->

- Option: <!-- [List the proposed options no longer open for consideration.] -->
- Rejection Reason: <!-- [List the reasons for the rejection: (the Bad traits)] -->

## If this enhancement will not be used often, can it be worked around with a few lines of script?

[If this enhancement will not be used often, can it be worked around with a few lines of script?]

## Is there a reason why this should be core and done by us?

[Is there a reason why this should be core and done by us?]

## References <!-- optional -->

- [Link type](link to decision) <!-- example: Refined by [xxx](yyyymmdd-xxx.md) -->
- <!-- numbers of links can vary -->

## Derivative License

Copyright (c) 2021 K. S. Ernest (iFire) Lee.

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
