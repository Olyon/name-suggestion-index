## Release Checklist

#### Update version, tag, and publish
- [ ] git checkout main
- [ ] git pull origin
- [ ] npm install
- [ ] npm run build
- [ ] Update version number in `package.json` and `README.md`
- [ ] npm run wikidata
- [ ] npm run dist
- [ ] git add . && git commit -m 'vA.B.C'
- [ ] git tag vA.B.C
- [ ] git push origin main vA.B.C
- [ ] npm publish
