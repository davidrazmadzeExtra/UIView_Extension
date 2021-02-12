# UIView Extension

UIView Extension for setting programmatic constraints

## Usage

```
let label = UILabel()
label.text = "Example text"

// Inside of viewDidLoad() in a UIViewController

view.addSubview(label)
label.anchor(top: view.topAnchor, left: view.leftAnchor, right: view.rightAnchor, paddingTop: 16, paddingLeft: 16, paddingRight: 16)

```
