# renovate-maven-test

#config.js
```
module.exports = {
  platform: 'github',
  labels: ['renovate'],
  extends: ['config:base', 'github>whitesource/merge-confidence:beta'],
  fetchReleaseNotes: true,
  docker: { enabled: false },
  python: { enabled: false },
  maven: { enabled: true },

  
  repositories: ['fmorva/renovate-maven-test'],
};
```
