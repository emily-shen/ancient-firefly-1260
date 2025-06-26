#issue repro for 9729

no issues with `npx wrangler dev`

but won't build with `npx wrangler deploy`

setting `"image_build_context": "../"` will fix the deploy issue
