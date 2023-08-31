## Hey, I’m @gorpello 👋


Hi, my name is Gianluca Orpello. 
I am an **Apple Certified Trainer** and a freelance Mentor in Italy. I specialize in iOS app design and development, web app design, and API design.
I also have knowledge in User Interaction, User Experience, and Project Management.



```swift
import SwiftUI

struct DeveloperProfile: View {

    let name: String = "Gianluca Orpello"
    let title: String = "Coding Mentor"
    
    let skills: [String] = [
      "Agile", "App Architecture", "Auto-Layout", "CLI tools with Swift", "Databases",
      "HTML/CSS", "Human Interface Guidelines", "JavaScript", "Public Speaking",
      "REST APIs", "Server Side Swift", "SpriteKit", "Storytelling", "Swift AWS Lambda Runtime",
      "Swift Playgrounds", "iOS", "ipadOS", "watchOS", "tvOS", "macOS", "WebKit",
      "Swift", "UIKit", "SwiftUI", "GIT", "Privacy", "And a Lot More..."
    ]

    var body: some View {
        VStack(alignment: .leading) {
            Text(name)
                .font(.title)
            Text(title)
                .font(.subheadline)
            Text("Skills")
                .font(.headline)
            ForEach(skills, id: \.self) { skill in
                Text(skill)
                    .font(.body)
            }
        }
    }
    
}
```

### 🧑‍💻🍿 A donkey developer with a dream of becoming a unicorn 🦄

I have always looked for new challenges to be able to grow professionally.
The desire for success has prompted me several times to look for new and challenging environments.

I am a passionate and empathetic developer at heart with experience in project design and management.

The experience at the [Apple Developer Academy](https://www.developeracademy.unina.it/en/) has taught me to work with people with different
skill sets and professional backgrounds to achieve a common goal. Teaching me to manage the workload to meet deadlines,
organising work on different projects, improving my analytical, critical thinking, and problem-solving skills.

### 🏍️ More About Me

**Apple Certified Trainer** <br>
Faculty & Graduated @ [Apple Developer Academy](https://www.developeracademy.unina.it/en/) <br>
👨‍💻 Software Engineer <br>
📲 Apple Enthusiast <br>
🏍 Motorbike Lover. <br>

- [If you need me](g.orpello@gmail.com) - No spam please 🙏
- [My website](https://www.gianlucaorpello.com) - Need an update sorry 👀🥺🙄
- [Linkedin](https://www.linkedin.com/in/gianlucaorpello/)
- [Twitter](https://twitter.com/GOrpello)
