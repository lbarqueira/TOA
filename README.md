# Tasks Of Affirmation

This is a wholesome todo list application. The purpose of this application is to help users 
stay organized in their day-to-day lives without feeling the pressure or guilt that can sometimes 
arise from tradition todo list applications.

As we build out this project, our goal will remain on how we can look after users and provide a 
wholesome and helpful experience as they become and stay organized.

## Live Streaming

This entire application will be built live on [Adam's Twitch channel](https://twitch.tv/adammc331). 
All streams will be recorded and archived on [YouTube](https://youtube.com/AdamMcNeilly) as well.


## Organization

All work on this project should be recorded in a relevant [issue](https://github.com/lbarqueira/TOA/issues), and tied to a corresponding 
GitHub [project](https://github.com/lbarqueira/TOA/projects).

## Stream History

[Stream History](https://github.com/AdamMc331/TOA/blob/development/StreamHistory.md#stream-history)


### Stream Two - Developer Experience

In this stream, we discuss a number of ways to help dev experience in Android like CI tooling and static analysis.

Date: September 8, 2021

YouTube: https://youtu.be/ePpbpLyYI1w

Blog: https://androidessence.com/essential-dev-experience-concepts-android

- GitHub Actions
- Danger
- Ktlint
- Detekt
- Git Hooks

### Important: This Stream Two, may serve as a template for a new Android Jetpack Compose app

### How to make this project serving as a template?

### Important Git CLI to retain:

```
// list of available branches
$ git branch

// -b (git branch then git checkout): creates and switches to, a new branch  TOA-4/git_hooks: 
$ git checkout -b TOA-4/git_hooks

// switch to main branch
$ git checkout main

// After commit, push, open pull request and merge branch TOA-4/git_hooks to main, I can delete it on remote (GitHub)
// Then locally, I update project:
$ git pull 

// Then:
// Deleting a branch LOCALLY
git branch -d TOA-4/git-hooks

```