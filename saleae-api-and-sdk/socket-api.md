# Socket API - Automation

The Socket API scripting utility allows users to programmatically configure our software and trigger captures.

This Socket API download requires the latest Saleae beta—1.2.5. If you need to use an older version of the Saleae software, please contact us.

Version **1.2.5+** Socket Interface C\# Example Application and Documentation:

[https://github.com/saleae/SaleaeSocketApi](https://github.com/saleae/SaleaeSocketApi)

Please contact us if you have any questions or feedback. The scripting interface will continue to evolve as we receive feedback from our customers.

### Enable the Logic Software for Scripting

{% hint style="info" %}
We highly recommend suppressing notifications and error messages while running your automation script. These notifications may block normal operation and can be suppressed by starting the application with the command line option below.

```text
-disablepopups
```
{% endhint %}

1. Check that you are using the [latest version of the Logic software](https://www.saleae.com/downloads/).
2. Open Options Menu  ![](https://trello-attachments.s3.amazonaws.com/5615390cb22fd44d4ccedc6f/336x266/5d5b89c169854861cae51f1c77d67605/open_options.png)
3. Select Preferences  ![](https://trello-attachments.s3.amazonaws.com/5615390cb22fd44d4ccedc6f/400x479/b8307eb7f45120d0f9cc172bbf565a40/select_preferences.PNG)
4. Open Developer Tab  ![](https://trello-attachments.s3.amazonaws.com/5615390cb22fd44d4ccedc6f/388x87/c290c691957c121514fb85f079378b2e/developer_tab.png)
5. Check box to enable socket server  ![](https://trello-attachments.s3.amazonaws.com/5615390cb22fd44d4ccedc6f/396x306/67677307eaf2bd57d85b18c834c92149/check_box.png)
6. Save Changes  ![](https://trello-attachments.s3.amazonaws.com/5615390cb22fd44d4ccedc6f/238x69/4634ba45ac78ad7d76bb59e779678bec/save_changes.png)
7. \(platform specific\) accept firewall changes

### Third-Party Implementations

C\# data logging UI:

[https://github.com/quarkng/SaleaeLogger](https://github.com/quarkng/SaleaeLogger)

C\# logging console application:

[https://github.com/DuckPaddle/LumberJack-for-Saleae](https://github.com/DuckPaddle/LumberJack-for-Saleae)

Python wrapper:

[https://github.com/ppannuto/python-saleae](https://github.com/ppannuto/python-saleae)

[https://pypi.python.org/pypi/saleae](https://pypi.python.org/pypi/saleae)

Python sample application:

[https://github.com/saleae/python-saleae-cli](https://github.com/saleae/python-saleae-cli)

If you would like to share your application, feel free to send us a link to it on any repository hosting provider, and we can share that link here.

### **Command Line Option**

For automated environments, you can launch the Logic software with a -socket command line option to cause the socket server to be enabled by default.

### Which Export Options are Available via Socket API?

The Socket API currently supports the raw export feature and the protocol-specific export feature. However, the socket API does not yet support exporting the protocol search results.

