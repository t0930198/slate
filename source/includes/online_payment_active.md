# Online Payment (Active)
## Diagram

```objective_c
int main (int argc, const char * argv[])
{
        NSAutoreleasePool *pool = [[NSAutoreleasePool alloc] init];
        NSLog (@"Hello, World!");
        [pool drain];
        return 0;
}
```

```swift
func tableView(tableView: UITableView!, numberOfRowsInSection section:    Int) -> Int {
return 10
}


func tableView(tableView: UITableView!, cellForRowAtIndexPath indexPath: NSIndexPath!) -> UITableViewCell! {
let cell: UITableViewCell = UITableViewCell(style: UITableViewCellStyle.Subtitle, reuseIdentifier: "MyTestCell")

cell.text = "Row #\(indexPath.row)"
cell.detailTextLabel.text = "Subtitle #\(indexPath.row)"

return cell
}
```


```java
package com.example.helloandroid;

import android.app.Activity;
import android.os.Bundle;

import android.widget.TextView;

public class HelloAndroid extends Activity {
    /** Called when the activity is first created. */
    @Override
    public void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        TextView tv = new TextView(this);
        tv.setText("Hello Android");
        setContentView(tv);
    }
}
```

![](/images/dia.png)

## Discription

  1.    
    1. Before using TapPay Connect ...
    2. Our recommendation for you is putting ...
  2.  
  3.  
  4.    
    1. call "TPCCOnlinePayB" on TPCC to get ...
