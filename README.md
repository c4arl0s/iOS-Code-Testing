# [go back to Overview](https://github.com/c4arl0s#test-driven-development-on-ios)

In order to update an existing Git submodule execute: (You might need permissions from Owner to get submodules)

```console
git submodule update --init --recursive
git pull --recurse-submodules
git submodule update --remote --merge
```

# Notes:

To run UI test on real device, different profile is required to configure as UITest target runs on different process as different app.

For simulator, developer provisioning profile is ok. But if you want to run UI Tests on real devices, you need separate developer provisioning profile.

# [iOS-Code-Testing](https://github.com/c4arl0s/iOS-Code-Testing#go-back-to-overview)

Project to implement Test Driven Development over an iOS App.

1. [x] [1. Introduction to Test-driven Development](https://github.com/c4arl0s/1-Introduction-to-Test-Driven-Development#1-introduction-to-test-driven-development-1)
2. [x] [2. Writing Your First Set of Unit Tests with Xcode](https://github.com/c4arl0s/2-Writing-Your-First-Set-of-Unit-Tests-with-Xcode#2-writing-your-first-set-of-unit-tests-with-xcode---content)
3. [x] [3. The MVVM Architectural Patter](https://github.com/c4arl0s/3-The-MVVM-Architectural-Pattern#3-the-mvvm-architectural-pattern---content)
4. [ ] [4. Applying TDD to the Model](https://github.com/c4arl0s/4-Applying-TDD-to-the-Model#4-applying-tdd-to-the-model---content)
5. [ ] 5. Applying TDD to View Controllers
6. [ ] 6. Applying TDD to Collection View Controllers
7. [ ] 7. Testing URL Session
8. [ ] 8. Working with Legacy Code
9. [ ] 9. Continuous Integration
10. [ ] 10. Introduction to Behavior-Driven Development
11. [ ] 11. Installing Quick
12. [ ] 12. Applying TDD and BDD Techniques
13. [ ] [13. Testing The User Interface](https://github.com/c4arl0s/13-testing-the-user-interface#go-back-to-overview) This chapter is equivalent to this other chapter: [7. User Interface tests](https://github.com/c4arl0s/7-User-Interface-Tests?tab=readme-ov-file#7-user-interface-tests---content)
