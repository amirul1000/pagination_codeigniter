"# pagination_codeigniter" 


Pagination in CodeIgniter ( PHP MySQL ) with Bootstrap CSS Tutorial 
=================================================================

CodeIgniter’s Pagination class is very easy to use, and it is 100% customizable, either dynamically or via stored preferences.

The $config array contains your configuration variables. It is passed to the $this-pagination-initialize  method as shown above. Although there are some twenty items you can configure, at minimum you need the three shown. Here is a description of what those items represent:

base_url This is the full URL to the controller class/function containing your pagination. In the example above, it is pointing to a controller called “Test” and a function called “page”. Keep in mind that you can re-route your URI if you need a different structure.

total_rows This number represents the total rows in the result set you are creating pagination for. Typically this number will be the total rows that your database query returned.
per_page The number of items you intend to show per page. In the above example, you would be showing 10 items per page.
The create_links method returns an empty string when there is no pagination to show.


Youtube Tutorial : https://youtu.be/GufGZ0-qVmU

Youtube Channel : https://www.youtube.com/channel/UC2Q4oWfoMQzi6AES8Vb2vQw?view_as=subscriber

Donate to Paypal : patabuz@gmail.com

https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=KHM59LRPNV3YY&source=url
