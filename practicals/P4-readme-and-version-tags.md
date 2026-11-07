# P4 – GitHub README and Version Tags

## Aim
Document the repository and learn how to mark a stable version with a Git tag.

## README purpose
A README introduces the project, explains its purpose, lists technologies and provides a practical index. The repository README is maintained at the root of this project.

## Version-tag commands
```bash
git tag -a v1.0.0 -m "First complete web development lab"
git tag
git push origin v1.0.0
```

To inspect a tag:
```bash
git show v1.0.0
```

To remove a tag if it was created incorrectly:
```bash
git tag -d v1.0.0
git push origin --delete v1.0.0
```

## Explanation
A tag is a named reference to a particular commit. An annotated tag stores a message and metadata. Pushing the tag publishes it to GitHub.

## Result
The README describes the repository and all practicals. The commands above document how to create and publish the first version tag.

## Conclusion
The repository documentation and Git version-tag workflow are recorded.
