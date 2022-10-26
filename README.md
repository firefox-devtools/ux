# Contributing to Firefox DevTools UX

Note: This project is currently paused.

Welcome, and thanks for your interest in contributing to DevTools UX! The issues in this repository are currently in need of some cleanup/updating; however, if you see something you would like to work on, please get in touch! —Victoria

## First Steps

1. Join the friendly [Firefox DevTools Slack](https://devtools-html-slack.herokuapp.com/) community!
   * The new `#ux` channel is a place for us designers to hang out, ask questions, post mockups for feedback, and offer feedback for other designers’ mockups. We’ll be communicating with everyone through this channel.
   * Feel free to introduce yourself or talk about general DevTools topics in `#general`
2. Check out the [Firefox DevTools design system](https://firefox-dev.tools/photon/).
   * This design system is a fork from the main [Firefox design system](https://design.firefox.com/photon/)

## Process

1. [Claim a UX issue](https://github.com/devtools-html/ux/issues) by commenting in it. Anything tagged [`good-first-issue`](https://github.com/devtools-html/ux/labels/good%20first%20issue) is a great place to start, especially if you're new to design. Feel free to ask on Slack for help in choosing a first task. (Some tasks have some preliminary work done, but may still be available.)

2. Once you have a task, it’s great to do a little research.  
   * Get ideas from similar UI in DevTools and Firefox. Download [Firefox Nightly](https://www.mozilla.org/en-US/firefox/channel/desktop/) to view the latest version of the UI. When possible, try to reuse already existing colors and other visuals in DevTools/Firefox.
   * Ask questions in Slack. Developers in panel-specific channels can help with questions about user needs and behaviors. You can also ask your own developer friends for ideas!
   * See what Chrome, Safari, and Edge are doing for similar features. Also check out other development tools, like Atom and Xcode.

3. Start working on the design. There are several ways to approach this, depending on the task.
   * Make a mockup. This could involve working in an existing Sketch file, modifying a screenshot, or recreating a mockup if you're interested in helping with our Sketch libraries. This is great for more involved visual changes that would be too much to code via the other methods. For small changes that really need to be tested on real content, this might not be practical. For more complex UX tasks, a low-fidelity wireframe is a great way to start.
   * Inspect the toolbox via the [toolbox-inspector](https://developer.mozilla.org/en-US/docs/Tools/Browser_Toolbox) to try out small CSS changes. This can be fraught with trouble due to the usual Inspector problem of no persistence features (it's in the plans!), but we use this all the time to quickly visualize a change.
   * Building and running Firefox (instructions below), and trying CSS changes right in the codebase. It can be tricky to get started, but is especially useful because then you can seamlessly move on to submitting a patch :).

4. Post high-res screenshots in the relevant github issue and on #ux to get feedback. Make iterations as needed.

5. Get a final sign-off from @victoria to send your design into development mode!

## Tips
* Take screenshots of every stage for your portfolio :)
* As a final step, icons should be saved/re-saved using Illustrator and follow the [SVG guidelines](https://developer.mozilla.org/en-US/docs/Mozilla/Developer_guide/SVG_Guidelines) for better performance. (A Mozilla person can help if you don't have a copy of Illustrator.) Other SVG tools can be great for this too.

## Implementing Your Own Design

Do you know HTML and CSS? If so, you can make your own design a reality! The friendly engineers of Firefox DevTools can help mentor you through the process of submitting a good patch. The biggest first step is building Firefox. Here are some guides:
* [Building Firefox for DevTools Development (Mac/Linux)](https://docs.firefox-dev.tools/getting-started/build.html)
   * Use the steps for [Artifact Builds](https://docs.firefox-dev.tools/getting-started/build.html#building-even-faster-with-artifact-builds) for much faster build times
* [Debugger Contribution Guide](https://github.com/devtools-html/debugger.html/blob/master/.github/CONTRIBUTING.md)
* [General Firefox Contribution Guide (Windows)](https://developer.mozilla.org/en-US/docs/Mozilla/Developer_guide/Introduction#Step_1_Build_Firefox_for_Desktop_or_Android)
* [Profiles](https://developer.mozilla.org/en-US/docs/Mozilla/Firefox/Multiple_profiles) for running multiple Firefoxes at the same time

## Communications

* [Slack: #ux channel](https://devtools-html-slack.herokuapp.com/)
* [Community video chat](https://appear.in/devtools-ux) (Meetings TBD)

## Mozilla People

Mentors:
- @victoria - Senior DevTools UX
- @yzen - Accessibility mentor
- @gl - Developer mentor

Project people:
- @Martin Balfanz - DesignTools PM (Inspector, RDM, Style Editor, Accessibility…)
- @digitarald - DevTools PM (Console, Debugger, Network…)
