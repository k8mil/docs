# git_commit


Directly commit the given file with the given message







git_commit |
-----|----
Supported platforms | ios, android, mac
Author | @KrauseFx



**3 Examples**

```ruby
git_commit(path: "./version.txt", message: "Version Bump")
```

```ruby
git_commit(path: ["./version.txt", "./changelog.txt"], message: "Version Bump")
```

```ruby
git_commit(path: ["./*.txt", "./*.md"], message: "Update documentation")
```





**Parameters**

Key | Description
----|------------
  `path` | The file you want to commit
  `message` | The commit message that should be used




<hr />
To show the documentation in your terminal, run
```no-highlight
fastlane action git_commit
```

<a href="https://github.com/fastlane/fastlane/blob/master/fastlane/lib/fastlane/actions/git_commit.rb" target="_blank">View source code</a>

<hr />

<a href="/actions"><b>Back to actions</b></a>
