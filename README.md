# Auto-Image-Download
## To Search and download image automatically

# Taking command line arguments from users
        # Taking command line arguments from users
        
        ### ('-k', '--keywords', help='delimited list input', type=str, required=False)
        ### ('-kf', '--keywords_from_file', help='extract list of keywords from a text file', type=str, required=False)
        ### ('-sk', '--suffix_keywords', help='comma separated additional words added after to main keyword', type=str, required=False)
        ### ('-pk', '--prefix_keywords', help='comma separated additional words added before main keyword', type=str, required=False)
        ### ('-l', '--limit', help='delimited list input', type=str, required=False)
        ### ('-f', '--format', help='download images with specific format', type=str, required=False,
                            choices=['jpg', 'gif', 'png', 'bmp', 'svg', 'webp', 'ico'])
        ### ('-u', '--url', help='search with google image URL', type=str, required=False)
        ### ('-x', '--single_image', help='downloading a single image from URL', type=str, required=False)
        ### ('-o', '--output_directory', help='download images in a specific main directory', type=str, required=False)
        ### ('-i', '--image_directory', help='download images in a specific sub-directory', type=str, required=False)
        ### ('-n', '--no_directory', default=False, help='download images in the main directory but no sub-directory', action="store_true")
        ### ('-d', '--delay', help='delay in seconds to wait between downloading two images', type=int, required=False)
        ### ('-co', '--color', help='filter on color', type=str, required=False,
                            choices=['red', 'orange', 'yellow', 'green', 'teal', 'blue', 'purple', 'pink', 'white', 'gray', 'black', 'brown'])
        ### ('-ct', '--color_type', help='filter on color', type=str, required=False,
                            choices=['full-color', 'black-and-white', 'transparent'])
        ### ('-r', '--usage_rights', help='usage rights', type=str, required=False,
                            choices=['labeled-for-reuse-with-modifications','labeled-for-reuse','labeled-for-noncommercial-reuse-with-modification','labeled-for-nocommercial-reuse'])
        ### ('-s', '--size', help='image size', type=str, required=False,
                            choices=['large','medium','icon','>400*300','>640*480','>800*600','>1024*768','>2MP','>4MP','>6MP','>8MP','>10MP','>12MP','>15MP','>20MP','>40MP','>70MP'])
        ### ('-es', '--exact_size', help='exact image resolution "WIDTH,HEIGHT"', type=str, required=False)
        ### ('-t', '--type', help='image type', type=str, required=False,
                            choices=['face','photo','clipart','line-drawing','animated'])
        ### ('-w', '--time', help='image age', type=str, required=False,
                            choices=['past-24-hours','past-7-days','past-month','past-year'])
        ### ('-wr', '--time_range', help='time range for the age of the image. should be in the format {"time_min":"MM/DD/YYYY","time_max":"MM/DD/YYYY"}', type=str, required=False)
        ### ('-a', '--aspect_ratio', help='comma separated additional words added to keywords', type=str, required=False,
                            choices=['tall', 'square', 'wide', 'panoramic'])
        ### ('-si', '--similar_images', help='downloads images very similar to the image URL you provide', type=str, required=False)
        ### ('-ss', '--specific_site', help='downloads images that are indexed from a specific website', type=str, required=False)
        ### ('-p', '--print_urls', default=False, help="Print the URLs of the images", action="store_true")
        ### ('-ps', '--print_size', default=False, help="Print the size of the images on disk", action="store_true")
        ### ('-pp', '--print_paths', default=False, help="Prints the list of absolute paths of the images",action="store_true")
        ### ('-m', '--metadata', default=False, help="Print the metadata of the image", action="store_true")
        ### ('-e', '--extract_metadata', default=False, help="Dumps all the logs into a text file", action="store_true")
        ### ('-st', '--socket_timeout', default=False, help="Connection timeout waiting for the image to download", type=float)
        ### ('-th', '--thumbnail', default=False, help="Downloads image thumbnail along with the actual image", action="store_true")
        ### ('-tho', '--thumbnail_only', default=False, help="Downloads only thumbnail without downloading actual images", action="store_true")
        ### ('-la', '--language', default=False, help="Defines the language filter. The search results are authomatically returned in that language", type=str, required=False,
                            choices=['Arabic','Chinese (Simplified)','Chinese (Traditional)','Czech','Danish','Dutch','English','Estonian','Finnish','French','German','Greek','Hebrew','Hungarian','Icelandic','Italian','Japanese','Korean','Latvian','Lithuanian','Norwegian','Portuguese','Polish','Romanian','Russian','Spanish','Swedish','Turkish'])
        ### ('-pr', '--prefix', default=False, help="A word that you would want to prefix in front of each image name", type=str, required=False)
        ### ('-px', '--proxy', help='specify a proxy address and port', type=str, required=False)
        ### ('-cd', '--chromedriver', help='specify the path to chromedriver executable in your local machine', type=str, required=False)
        ### ('-ri', '--related_images', default=False, help="Downloads images that are similar to the keyword provided", action="store_true")
        ### ('-sa', '--safe_search', default=False, help="Turns on the safe search filter while searching for images", action="store_true")
        ### ('-nn', '--no_numbering', default=False, help="Allows you to exclude the default numbering of images", action="store_true")
        ### ('-of', '--offset', help="Where to start in the fetched links", type=str, required=False)
        ### ('-nd', '--no_download', default=False, help="Prints the URLs of the images and/or thumbnails without downloading them", action="store_true")
        ### ('-iu', '--ignore_urls', default=False, help="delimited list input of image urls/keywords to ignore", type=str)
        ### ('-sil', '--silent_mode', default=False, help="Remains silent. Does not print notification messages on the terminal", action="store_true")
        ### ('-is', '--save_source', help="creates a text file containing a list of downloaded images along with source page url", type=str, required=False)

        ### ('-k', '--keywords', help='delimited list input', type=str, required=False)
        ### ('-kf', '--keywords_from_file', help='extract list of keywords from a text file', type=str, required=False)
        ### ('-sk', '--suffix_keywords', help='comma separated additional words added after to main keyword', type=str, required=False)
        ### ('-pk', '--prefix_keywords', help='comma separated additional words added before main keyword', type=str, required=False)
        ### ('-l', '--limit', help='delimited list input', type=str, required=False)
        ### ('-f', '--format', help='download images with specific format', type=str, required=False,
                            choices=['jpg', 'gif', 'png', 'bmp', 'svg', 'webp', 'ico'])
        ### ('-u', '--url', help='search with google image URL', type=str, required=False)
        ### ('-x', '--single_image', help='downloading a single image from URL', type=str, required=False)
        ### ('-o', '--output_directory', help='download images in a specific main directory', type=str, required=False)
        ### ('-i', '--image_directory', help='download images in a specific sub-directory', type=str, required=False)
        ### ('-n', '--no_directory', default=False, help='download images in the main directory but no sub-directory', action="store_true")
        ### ('-d', '--delay', help='delay in seconds to wait between downloading two images', type=int, required=False)
        ### ('-co', '--color', help='filter on color', type=str, required=False,
                            choices=['red', 'orange', 'yellow', 'green', 'teal', 'blue', 'purple', 'pink', 'white', 'gray', 'black', 'brown'])
        ### ('-ct', '--color_type', help='filter on color', type=str, required=False,
                            choices=['full-color', 'black-and-white', 'transparent'])
        ### ('-r', '--usage_rights', help='usage rights', type=str, required=False,
                            choices=['labeled-for-reuse-with-modifications','labeled-for-reuse','labeled-for-noncommercial-reuse-with-modification','labeled-for-nocommercial-reuse'])
        ### ('-s', '--size', help='image size', type=str, required=False,
                            choices=['large','medium','icon','>400*300','>640*480','>800*600','>1024*768','>2MP','>4MP','>6MP','>8MP','>10MP','>12MP','>15MP','>20MP','>40MP','>70MP'])
        ### ('-es', '--exact_size', help='exact image resolution "WIDTH,HEIGHT"', type=str, required=False)
        ### ('-t', '--type', help='image type', type=str, required=False,
                            choices=['face','photo','clipart','line-drawing','animated'])
        ### ('-w', '--time', help='image age', type=str, required=False,
                            choices=['past-24-hours','past-7-days','past-month','past-year'])
        ### ('-wr', '--time_range', help='time range for the age of the image. should be in the format {"time_min":"MM/DD/YYYY","time_max":"MM/DD/YYYY"}', type=str, required=False)
        ### ('-a', '--aspect_ratio', help='comma separated additional words added to keywords', type=str, required=False,
                            choices=['tall', 'square', 'wide', 'panoramic'])
        ### ('-si', '--similar_images', help='downloads images very similar to the image URL you provide', type=str, required=False)
        ### ('-ss', '--specific_site', help='downloads images that are indexed from a specific website', type=str, required=False)
        ### ('-p', '--print_urls', default=False, help="Print the URLs of the images", action="store_true")
        ### ('-ps', '--print_size', default=False, help="Print the size of the images on disk", action="store_true")
        ### ('-pp', '--print_paths', default=False, help="Prints the list of absolute paths of the images",action="store_true")
        ### ('-m', '--metadata', default=False, help="Print the metadata of the image", action="store_true")
        ### ('-e', '--extract_metadata', default=False, help="Dumps all the logs into a text file", action="store_true")
        ### ('-st', '--socket_timeout', default=False, help="Connection timeout waiting for the image to download", type=float)
        ### ('-th', '--thumbnail', default=False, help="Downloads image thumbnail along with the actual image", action="store_true")
        ### ('-tho', '--thumbnail_only', default=False, help="Downloads only thumbnail without downloading actual images", action="store_true")
        ### ('-la', '--language', default=False, help="Defines the language filter. The search results are authomatically returned in that language", type=str, required=False,
                            choices=['Arabic','Chinese (Simplified)','Chinese (Traditional)','Czech','Danish','Dutch','English','Estonian','Finnish','French','German','Greek','Hebrew','Hungarian','Icelandic','Italian','Japanese','Korean','Latvian','Lithuanian','Norwegian','Portuguese','Polish','Romanian','Russian','Spanish','Swedish','Turkish'])
        ### ('-pr', '--prefix', default=False, help="A word that you would want to prefix in front of each image name", type=str, required=False)
        ### ('-px', '--proxy', help='specify a proxy address and port', type=str, required=False)
        ### ('-cd', '--chromedriver', help='specify the path to chromedriver executable in your local machine', type=str, required=False)
        ### ('-ri', '--related_images', default=False, help="Downloads images that are similar to the keyword provided", action="store_true")
        ### ('-sa', '--safe_search', default=False, help="Turns on the safe search filter while searching for images", action="store_true")
        ### ('-nn', '--no_numbering', default=False, help="Allows you to exclude the default numbering of images", action="store_true")
        ### ('-of', '--offset', help="Where to start in the fetched links", type=str, required=False)
        ### ('-nd', '--no_download', default=False, help="Prints the URLs of the images and/or thumbnails without downloading them", action="store_true")
        ### ('-iu', '--ignore_urls', default=False, help="delimited list input of image urls/keywords to ignore", type=str)
        ### ('-sil', '--silent_mode', default=False, help="Remains silent. Does not print notification messages on the terminal", action="store_true")
        ### ('-is', '--save_source', help="creates a text file containing a list of downloaded images along with source page url", type=str, required=False)

