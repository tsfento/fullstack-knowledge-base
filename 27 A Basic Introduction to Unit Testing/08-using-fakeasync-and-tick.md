# Using "fakeAsync" and "tick"
01. Copied waitForAsync test from previous video
02. Changed waitForAsync to fakeAsync
03. Got rid of fixture.whenStable().then(), moving expect back outside
04. Called tick() between detectChanges and expect
05. In a fakeAsync environment tick executes asynchronous tasks immediately
06. Both methods, waitForAsync and fakeAsync are basically the same