# iMessage mobile layout for TiddlyWiki5

[Demo](https://tiddly-gittly.github.io/mobile-imessage-layout/)

Simple chat style (or Twitter style) layout for mobile. Quickly input todo and thoughts in few seconds.

[Forum thread - Design a Layout for Mobile](https://talk.tiddlywiki.org/t/design-a-layout-for-mobile/5781)

## Development

See [tiddly-gittly/Modern.TiddlyDev](https://github.com/tiddly-gittly/Modern.TiddlyDev) for detail.

There are some scripts you can run to boost your development.

After `pnpm i`:

- `npm run dev` to auto pack the plugin and run a demo site. Your change in the src directory will automatically refresh the site.

### After the plugin is complete

#### Publish

Enable github action in your repo (in your github repo - setting - action - general) if it is not allowed, and when you tagging a new version `vx.x.x` in a git commit and push, it will automatically publish to the github release.

#### Demo

[Demo](https://tiddly-gittly.github.io/mobile-imessage-layout/)

You will get a Github Pages demo site automatically after publish. If it is 404, you may need to manually enable Github Pages in your github repo:

Settings - Pages (on left side) - Build and deployment- Source - choose `"Github Actions"`

Next time you trigger a publish, the site will be updated. You can see the site link in Settings - Pages
