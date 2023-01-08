## Hey there, I am Sam! 👋

```swift
import AboutMe

public struct Sam: About {
    // 🔭 I’m currently working on
    public var currentWorkplace: Workplace {
        return Workplace(
            name: "Ravn"
            position: "Sr. Lead iOS Engineer"
        )
    }

    // 👨‍💻 Having fun with these
    public var programmingLanguages: [Language] {
        return [
            Language(name: "Swift"),
            Language(name: "Objective-C"),
            Language(name: "Python"),
            Language(name: "C++")
        ]
    }

    // 📱 Ask me about iOS
    public var technologies: [IOSTechnology] {
        return [
            IOSTechnology(name: "UIKit"),
            IOSTechnology(name: "RxSwift"),
            IOSTechnology(name: "SwiftUI"),
            IOSTechnology(name: "Combine")
        ]
    }

    // ⚡ Fun fact
    public func executeSwiftWithATwist() {
        print("I love working on Raspberry Pi projects using Swift! Check out my libraries 👀")

        let libraries: [Library] = [
            Library(
                name: "SwiftyXBee",
                purpose: "A Swift library for communicating with XBee radios in API mode"
            ),
            Library(
                name: "SwiftFlowMeter",
                purpose: "A Swift library for using Hall effect based water flow sensors."
            ),
            Library(
                name: " SwiftySHT20",
                purpose: "A Swift library for the I2C SHT20 Humidity and Temperature Sensor."
            )
        ]

        publish(libraries: libraries)
    }
}
```

## Every day is a work in progress 🚧

[![Sam's GitHub stats](https://github-readme-stats.vercel.app/api?username=samco182&hide=contribs&count_private=true&&show_icons=true&theme=city_lights&show_owner=true)](https://github.com/anuraghazra/github-readme-stats)

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=samco182&layout=compact&theme=city_lights&card_width=445)](https://github.com/anuraghazra/github-readme-stats)


## Feel free to reach me 📫

<p >
    <a style="margin-right: 8px"  href="https://www.linkedin.com/in/samuel-cornejo/" target="_blank">
        <img src="https://img.shields.io/badge/Samuel_Cornejo-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white"/>
    </a> 
    <a style="margin-right: 8px" href="https://twitter.com/samco182" target="_blank">
        <img src="https://img.shields.io/badge/twitter-%231DA1F2.svg?style=for-the-badge&logo=Twitter&logoColor=white">
    </a>
    <a href="mailto:sam.ach1990@gmail.com" target="_blank">
        <img src="https://img.shields.io/badge/gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white">
    </a>
</p>