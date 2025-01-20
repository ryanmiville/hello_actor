# hello_actor

```
tprof:profile(hello_actor, main, [], #{type => call_memory}).
```

```
****** Process <0.301.0>  --  100.00% of total ***
FUNCTION                                      CALLS           WORDS         PER CALL  [     %]
maps:iterator/2                                   1               2             2.00  [  0.00]
erts_internal:map_next/3                          1               4             4.00  [  0.00]
maps:map_1/3                                      2               5             2.50  [  0.00]
hello_actor:greeter/0                             1               5             5.00  [  0.00]
gleam_erlang_ffi:'-map_selector/2-fun-1-'/3       1               5             5.00  [  0.00]
maps:from_list/1                                  1               6             6.00  [  0.00]
gleam_erlang_ffi:map_selector/2                   1               7             7.00  [  0.00]
hello_actor:app_init/0                            1               8             8.00  [  0.00]
gleam@otp@actor:initialise_actor/2                1              12            12.00  [  0.00]
erlang:apply/2                                    1              19            19.00  [  0.00]
erlang:spawn_link/1                             101             202             2.00  [  0.00]
gleam@otp@actor:'-init_selector/2-fun-0-'/1     100             300             3.00  [  0.00]
erlang:monitor/2                                101             303             3.00  [  0.00]
gleam@otp@actor:'-start_spec/1-fun-1-'/1        101             303             3.00  [  0.00]
gleam@erlang@process:send/2                     101             303             3.00  [  0.00]
gleam@erlang@process:monitor_process/1          101             303             3.00  [  0.00]
gleam_erlang_ffi:merge_selector/2               102             306             3.00  [  0.00]
erlang:make_ref/0                               103             309             3.00  [  0.00]
gleam@otp@actor:continue/1                      100             400             4.00  [  0.00]
hello_actor:app_loop/2                          100             400             4.00  [  0.00]
gleam@erlang@process:new_subject/0              103             412             4.00  [  0.00]
gleam@otp@actor:start_spec/1                    101             505             5.00  [  0.00]
gleam@erlang@process:selecting_record3/3        101             707             7.00  [  0.00]
gleam@erlang@process:selecting/3                103             721             7.00  [  0.00]
hello_actor:bot/1                               100             900             9.00  [  0.00]
maps:merge/2                                    102            1018             9.98  [  0.00]
gleam@erlang@process:'-selecting/3-fun-0-'/2    201            1104             5.49  [  0.00]
gleam@otp@actor:loop/1                          101            1300            12.87  [  0.00]
gleam_erlang_ffi:insert_selector_handler/3      406            4462            10.99  [  0.00]
gleam_erlang_ffi:select/2                       202  35042736847773  173478895286.00  [100.00]
```
