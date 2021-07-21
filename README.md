# arango-data-loader

```
yarn install
yarn test-loader
```

## Notes

This code was excised from another project.  A few enhancements are needed in order for this to be generally useful, which is the focus for the tasks outlined in the Alpha 0.0.1 roadmap

The follow-on Release, 1.0.0 focuses on making `arango-spreadsheet-loader` a full featured, fully tested, arango data and graph loading tool

## Restrictions

Currently the arangodb server username/password is hard coded in `load-spreadsheet.js`.

### Roadmap 0.0.1 (alpha)

- [ ] get arango creds from env/command line
- [ ] evolve deprecated useDatabase() -> createDatabase()
- [ ] remove returning of loaded data optional
- [ ] evolve command line load-spreadsheet.js -> bin/arango-loader (or similar)
- [ ] build scripts / packaging for npm
- [ ] documentation for 0.0.1
- [ ] publish

### Roadmap 1.0.0

- [ ] Implement graphs
- [ ] Implement data type specifiers for document fields
- [ ] Add tests
- [ ] Update documentation
- [ ] publish
