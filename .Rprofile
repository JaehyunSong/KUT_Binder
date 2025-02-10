cat("高知工科大学冬季集中講義（宋）")
print(system("cat ~/.config/rstudio/rstudio-prefs.json", intern = TRUE) == "{}")
print(!("rstudio-prefs.json" %in% system("ls ~/.config/rstudio/", intern = TRUE)))
print((attr(system("cat ~/.config/rstudio/rstudio-prefs.json", intern = TRUE), "status") == 1))
if ((system("cat ~/.config/rstudio/rstudio-prefs.json", intern = TRUE) == "{}") | !("rstudio-prefs.json" %in% system("ls ~/.config/rstudio/", intern = TRUE)) | (attr(system("cat ~/.config/rstudio/rstudio-prefs.json", intern = TRUE), "status") == 1)) {
    system("mv rstudio-prefs.json ~/.config/rstudio/rstudio-prefs.json")
}