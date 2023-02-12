import UIKit

class ViewController: UIViewController {

    // Declare a variable to keep track of the counter
    var counter = 0

    // Outlet for the label to display the counter value
    @IBOutlet weak var counterLabel: UILabel!

    // Action triggered by the button click to increment the counter
    @IBAction func incrementCounter(_ sender: UIButton) {
        counter += 1
        updateCounterLabel()
    }

    override func viewDidLoad() {
        super.viewDidLoad()
        // Set the initial value of the counter label
        updateCounterLabel()
    }

    // Function to update the counter label
    func updateCounterLabel() {
        counterLabel.text = "Counter: \(counter)"
    }
}
