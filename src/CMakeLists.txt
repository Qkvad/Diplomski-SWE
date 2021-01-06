add_executable("diplomski" diplomski.cc driver.hh hyperbolicdg.hh numericalflux.hh shallowwater.hh shallowwaterproblem.hh)
target_link_dune_default_libraries("diplomski")

dune_symlink_to_source_files(FILES test.ini)
