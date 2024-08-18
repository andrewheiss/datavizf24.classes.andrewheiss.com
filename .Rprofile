options(
  repos = c(
    CRAN = "https://packagemanager.posit.co/cran/latest"
  ),
  renv.config.ppm.enabled = TRUE,
  renv.config.pak.enabled = TRUE
)

options(tigris_use_cache = TRUE)

source("renv/activate.R")

# Run the global .Rprofile if it exists
if (file.exists("~/.Rprofile")) {
  base::sys.source("~/.Rprofile", envir = environment())
}