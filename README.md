# Kortelės bugs

The page behind https://tomilianas.github.io/korteles-bugs/ : it lists the bug reports sent from the
game's temporary "Report a bug" button (Supabase table `public.bugs`) and can delete them.

It uses only the public (publishable) Supabase key, the one that already ships in the game. Status
changes are made with `tools/bugs.mjs` in the game repo.
