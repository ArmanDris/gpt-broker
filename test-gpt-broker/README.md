# test-gpt-broker

This is its own package, it requires its own .env and dependencies. 
test-gpt-broker will perform end to end testing on gpt-broker to make 
sure all of its functionality is there.

### To run tests:

Make sure there is a `.env` in this directory with:

~~~
SUPABASE_URL=<supabase_url>
SUPABASE_ANON_KEY=<supabase_anon_key>
SUPABASE_EMAIL=<admin@skillsync.work>
SUPABASE_PASSWORD=<supabase_account_password>
~~~

Then run:  
~~~
pnpm i
pnpm test
~~~
