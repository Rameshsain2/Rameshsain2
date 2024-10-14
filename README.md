- 👋 Hi, I’m @Rameshsain2
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
Rameshsain2/Rameshsain2 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
            - name: Upload a Build Artifact
  uses: actions/upload-artifact@v4.4.3
  with:
    # Artifact name
    name: # optional, default is artifact
    # A file, directory or wildcard pattern that describes what to upload
    path: 
    # The desired behavior if no files are found using the provided path.
Available Options:
  warn: Output a warning but do not fail the action
  error: Fail the action with an error message
  ignore: Do not output any warnings or errors, the action does not fail

    if-no-files-found: # optional, default is warn
    # Duration after which artifact will expire in days. 0 means using default retention.
Minimum 1 day. Maximum 90 days unless changed from the repository settings page.

    retention-days: # optional
    # The level of compression for Zlib to be applied to the artifact archive. The value can range from 0 to 9: - 0: No compression - 1: Best speed - 6: Default compression (same as GNU Gzip) - 9: Best compression Higher levels will result in better compression, but will take longer to complete. For large files that are not easily compressed, a value of 0 is recommended for significantly faster uploads.

    compression-level: # optional, default is 6
    # If true, an artifact with a matching name will be deleted before a new one is uploaded. If false, the action will fail if an artifact for the given name already exists. Does not fail if the artifact does not exist.

    overwrite: # optional, default is false
    # If true, hidden files will be included in the artifact. If false, hidden files will be excluded from the artifact.

    include-hidden-files: # optional, default is false
          ![Uploading IMG_20241013_203313_229.jpg…]()
