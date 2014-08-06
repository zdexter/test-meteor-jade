# meteor-jade 0.2.6 + iron-router 0.8.2

A repository to demonstrate a problem with Meteor 0.8.3, the Meteor coffeescript package, and atmosphere packages meteor-jade and iron-router.

## Issue Report

```
Exception from Deps recompute function: Error: Couldn't find a template named "home" or "home". Are you sure you defined it?
    at null.render (http://localhost:3000/packages/iron-dynamic-template.js?815426b0813770e9a7efbbc9d96521faa2de98bf:206:17)
    at doRender (http://localhost:3000/packages/blaze.js?309c2a3b573dca998c07c493ba4953d451b2c963:1857:25)
    at http://localhost:3000/packages/blaze.js?309c2a3b573dca998c07c493ba4953d451b2c963:1805:16
    at Object.Blaze.withCurrentView (http://localhost:3000/packages/blaze.js?309c2a3b573dca998c07c493ba4953d451b2c963:2038:12)
    at viewAutorun (http://localhost:3000/packages/blaze.js?309c2a3b573dca998c07c493ba4953d451b2c963:1804:18)
    at Deps.Computation._compute (http://localhost:3000/packages/deps.js?d9b2b2601bdab0f57291b38e7974a7190b8aac01:214:36)
    at new Deps.Computation (http://localhost:3000/packages/deps.js?d9b2b2601bdab0f57291b38e7974a7190b8aac01:148:10)
    at Object.Deps.autorun (http://localhost:3000/packages/deps.js?d9b2b2601bdab0f57291b38e7974a7190b8aac01:362:11)
    at Blaze.View.autorun (http://localhost:3000/packages/blaze.js?309c2a3b573dca998c07c493ba4953d451b2c963:1803:16)
    at http://localhost:3000/packages/blaze.js?309c2a3b573dca998c07c493ba4953d451b2c963:1851:10 debug.js:41
```