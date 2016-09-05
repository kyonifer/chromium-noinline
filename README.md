This patchset will make it so that completions from previous search terms 
(and previously visited urls in the history) will still appear, but by 
default it will actually go to what you type in, not some completion 
chromium injects without asking. For example, pre-patch if you type 
"www.bob.com<enter>" you might actually end up going to 
"www.bob.com/foo/bar" if you had visited that previously. Patches are 
generated off of chromium-53.0.2785.89.