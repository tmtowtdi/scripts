# scripts
Various scripts I find useful.

## raks
Poor-man's rakudobrew, I guess, but it does what I need it to do, assuming:
- you have one or more Rakudo installations in ~/, named ".rakudo-(ANY STRING)"
- ~/.rakudo is a symlink pointing to one of those installations
- ~/.rakudo/bin/ is in your PATH and contains "perl6"

Drop 'raks' into your PATH, run "perl -cw raks" and install the prereqs until you stop 
getting errors (yeah I know that's lazy and I should have a makefile).  Once you stop 
getting errors, "raks -h" for usage.

