# Maven

Hi there! This is YuutaW's personal maven repository! Some personal libraries are stored here in order to avoid some additoinal publishing fees.

# How to use?

For **each** of your Gradle modules you want to use this repository, add this line to the **module level** gradle file, for example:

`project/app/build.gradle`:

```grooxy
repositories {
    ... (other lines)
    maven {
        url 'https://maven.yuuta.dev'
    }
    ... (other lines)
}
```

# Browse libraries

The static web page does not support browsing, so you can alternately the Git repo: [Trumeet/Maven](https://github.com/Trumeet/Maven)

# Licenses

Some of them are SDKs of non-open projects. You should not self-host them or republish any of them. For open-source libraries hosted here, see license files for each of them.
