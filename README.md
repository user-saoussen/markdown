
markdown_tool [options] <article_file_path_or_url>

options:
  -h, --help            show this help message and exit
  -D {disabled,names_hashing,content_hash}, --deduplication-type {disabled,names_hashing,content_hash}
                        Deduplicate images, using content hash or SHA1(image_name) (default: disabled)
  -d IMAGES_DIRNAME, --images-dirname IMAGES_DIRNAME
                        Folder in which to download images (possible variables: $article_name, $time, $date, $dt, $base_url) (default: images)
  -a, --skip-all-incorrect
                        skip all incorrect images (default: False)
  -E, --download-incorrect-mime
                        download "images" with unrecognized MIME type (default: False)
  -s SKIP_LIST, --skip-list SKIP_LIST
                        skip URL's from the comma-separated list (or file with a leading '@') (default: None)
  -i {md,html,md+html,html+md}, --input-format {md,html,md+html,html+md}
                        input format (default: md)
  -l, --process-local-images
                        [DEPRECATED] Process local images (default: False)
  -n, --replace-image-names
                        Replace image names, using content hash (default: False)
  -o {md,html}, --output-format {md,html}
                        output format (default: md)
  -p IMAGES_PUBLIC_PATH, --images-public-path IMAGES_PUBLIC_PATH
                        Public path to the folder of downloaded images (possible variables: $article_name, $time, $date, $dt, $base_url)
  -P, --prepend-images-with-path
                        Save relative images paths (default: False)
  -R, --remove-source   Remove or replace source file (default: False)
  -t DOWNLOADING_TIMEOUT, --downloading-timeout DOWNLOADING_TIMEOUT
                        how many seconds to wait before downloading will be failed (default: -1)
  -O OUTPUT_PATH, --output-path OUTPUT_PATH
                        article output file name or path
  --verbose, -v         More verbose logging (default: False)
  --version             return version number
