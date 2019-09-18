# skz_web_wrapper
This wraps www::mechanize and duplicates the basic function calls, biggest thing is auto requesting after timeouts.  Will first pause rand() < 30 seconds, then after 3 failures it will pause 60 seconds, then 5 minutes...this will also start to change and use random user agents.  

#skz_util
This has a bunch of cool stuff, everything from using regexes to clean a string or an array, manipulates dates to different dates (even written dates to MySQL format), use regex to extract a link, a date, a number, some pretty print functions, etc etc.   BTW don't "use" it, just make sure its in your library and call function directly 
     skz_util::clean_all( $str );

Here's a list of all the stuff in skz_util. 

     sub clean_all
     sub clean_all_tags
     sub trim_hash
     sub clean_hash
     sub clean_trim
     sub timestamp
     sub get_day_stamp
     sub get_timestamp
     sub convert_mdy_to_sql
     sub convert_sql_to_mdy
     sub split_date_and_time_for_sql
     sub convert_date_to_sql
     sub convert_date_to_short
     sub date_to_sql
     sub parse_time_from_sql
     sub parse_date
     sub convert_letter_date_to_sql
     sub random
     sub time_w_meridian_to_sql
     sub process_time_to_sql
     sub find_in_content_tag
     sub regex_clean_trim
     sub regex_extract_link
     sub regex_extract_number
     sub regex_extract_date
     sub find_regex_in_string
     sub uniq
     sub search_term_against_list
     sub search_term_against_list_pure
     sub phash
     sub parray
     sub print_char_codes
     sub print_hash
     sub print_hash_sorted
     sub print_array
     sub clean_tbl_for_view
     sub trim
     sub clean_small_date
     sub remove_zero_from_date
     sub add_leading_zeros
     sub test_col_vs_str_layout
     sub test_str_vs_str_layout
     sub dump_array_to_file
     sub dump_file
     sub undump_file
     sub undump_file_str
     sub print_all_methods_in_package
     sub sentence_case
     
