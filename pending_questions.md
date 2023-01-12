TODO: delete before merging PR
- Should we test cache layout in Windows ?
- Should we run Windows tests with and without symlinks ? 
- How to set file permissions on blobs in Windows ? (not the umask solution). Is it worth testing ?
- How to handle awful filenames on Windows (with special characters in it) ? See tests `StagingCachedDownloadOnAwfulFilenamesTest`. Related to https://github.com/huggingface/huggingface_hub/issues/1161.