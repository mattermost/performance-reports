### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| SystemStore.Get | avg | 43ms | 113ms | 70ms | 161.59
| ProductNoticesStore.ClearOldNotices | avg | 3ms | 6ms | 3ms | 85.97
| JobStore.GetNewestJobByStatusesAndType | avg | 62ms | 87ms | 25ms | 40.41
| SessionStore.GetSessionsExpired | avg | 42ms | 55ms | 13ms | 30.72
| PostStore.AnalyticsPostCount | avg | 6.834s | 8.774s | 1.94s | 28.39
| UserStore.Count | avg | 187ms | 226ms | 39ms | 20.85
| PluginStore.List | avg | 89ms | 102ms | 13ms | 14.60
| JobStore.UpdateStatus | avg | 16ms | 18ms | 2ms | 12.13
| PostPriorityStore.GetForPost | avg | 70ms | 78ms | 8ms | 11.45
| JobStore.UpdateStatusOptimistically | avg | 21ms | 23ms | 2ms | 9.68
| ChannelStore.GetMember | avg | 33ms | 36ms | 3ms | 9.17
| ChannelStore.GetTeamChannels | avg | 168ms | 181ms | 13ms | 7.74
| UserAccessTokenStore.GetByToken | avg | 82ms | 87ms | 5ms | 6.11
| ChannelStore.GetChannelsByUser | avg | 69ms | 73ms | 4ms | 5.77
| ChannelStore.AutocompleteInTeamForSearch | avg | 420ms | 444ms | 24ms | 5.71
| ThreadStore.GetThreadFollowers | avg | 71ms | 75ms | 4ms | 5.64
| TeamStore.GetTeamsForUser | avg | 60ms | 63ms | 3ms | 5.00
| ThreadStore.GetTotalThreads | avg | 68ms | 71ms | 3ms | 4.40
| UserStore.Search | avg | 273ms | 285ms | 12ms | 4.39
| ChannelStore.Autocomplete | avg | 458ms | 477ms | 19ms | 4.15
| UserStore.AutocompleteUsersInChannel | avg | 637ms | 663ms | 26ms | 4.08
| JobStore.GetCountByStatusAndType | avg | 73ms | 76ms | 3ms | 4.08
| ChannelStore.SearchGroupChannels | avg | 99ms | 103ms | 4ms | 4.06
| PostStore.GetPostsSince | avg | 123ms | 128ms | 5ms | 4.05
| SessionStore.Save | avg | 74ms | 77ms | 3ms | 4.05
| ThreadStore.GetTeamsUnreadForUser | avg | 100ms | 104ms | 4ms | 4.00
| UserStore.GetForLogin | avg | 54ms | 56ms | 2ms | 3.68
| ChannelStore.GetMemberForPost | avg | 57ms | 59ms | 2ms | 3.50
| FileInfoStore.Get | avg | 61ms | 63ms | 2ms | 3.30
| TeamStore.GetTeamsByUserId | avg | 61ms | 63ms | 2ms | 3.26
| ThreadStore.GetThreadsForUser | avg | 96ms | 99ms | 3ms | 3.12
| ThreadStore.GetTotalUnreadMentions | avg | 68ms | 70ms | 2ms | 2.96
| UserStore.GetUnreadCountForChannel | avg | 68ms | 70ms | 2ms | 2.93
| ThreadStore.GetTotalUnreadThreads | avg | 69ms | 71ms | 2ms | 2.91
| ChannelStore.GetSidebarCategoriesForTeamForUser | avg | 207ms | 213ms | 6ms | 2.89
| ThreadStore.GetMembershipForUser | avg | 70ms | 72ms | 2ms | 2.86
| GroupStore.GetGroups | avg | 74ms | 76ms | 2ms | 2.71
| PostPersistentNotificationStore.GetSingle | avg | 75ms | 77ms | 2ms | 2.67
| UserStore.GetProfilesByUsernames | avg | 78ms | 80ms | 2ms | 2.58
| PostStore.GetPostsAfter | avg | 80ms | 82ms | 2ms | 2.51
| ChannelStore.GetMembersForUser | avg | 82ms | 84ms | 2ms | 2.43
| ChannelStore.GetChannels | avg | 89ms | 91ms | 2ms | 2.25
| PostStore.GetPostsBefore | avg | 93ms | 95ms | 2ms | 2.14
| StatusStore.GetByIds | avg | 109ms | 111ms | 2ms | 1.84
| ProductNoticesStore.View | avg | 122ms | 124ms | 2ms | 1.64
| PostStore.Get | avg | 184ms | 186ms | 2ms | 1.09
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| SystemStore.Get | p99 | 99ms | 247ms | 148ms | 149.49
| ProductNoticesStore.ClearOldNotices | p99 | 10ms | 24ms | 14ms | 142.86
| JobStore.UpdateOptimistically | p99 | 94ms | 175ms | 81ms | 86.17
| ReactionStore.GetForPost | p99 | 5ms | 9ms | 4ms | 80.02
| UserStore.GetUnreadCount | p99 | 687ms | 761ms | 74ms | 10.77
| UserAccessTokenStore.GetByToken | p99 | 823ms | 900ms | 77ms | 9.35
| PostStore.SetPostReminder | p99 | 432ms | 468ms | 36ms | 8.33
| PostPriorityStore.GetForPost | p99 | 790ms | 847ms | 57ms | 7.22
| PreferenceStore.DeleteCategoryAndName | p99 | 395ms | 418ms | 23ms | 5.82
| UserStore.GetProfileByIds | p99 | 94ms | 99ms | 5ms | 5.33
| ChannelStore.GetChannelsByUser | p99 | 701ms | 729ms | 28ms | 3.99
| ChannelStore.Autocomplete | p99 | 8.065s | 8.277s | 212ms | 2.63
| ChannelStore.GetMember | p99 | 463ms | 474ms | 11ms | 2.38
| ChannelStore.GetMembers | p99 | 1.263s | 1.292s | 29ms | 2.30
| TeamStore.GetTeamsForUser | p99 | 662ms | 677ms | 15ms | 2.27
| ThreadStore.GetTotalUnreadMentions | p99 | 761ms | 778ms | 17ms | 2.24
| UserStore.Search | p99 | 2.055s | 2.099s | 44ms | 2.14
| ThreadStore.GetTeamsUnreadForUser | p99 | 1.094s | 1.117s | 23ms | 2.10
| ChannelStore.Save | p99 | 890ms | 906ms | 16ms | 1.80
| PostStore.Update | p99 | 452ms | 460ms | 8ms | 1.77
| SessionStore.Save | p99 | 741ms | 754ms | 13ms | 1.75
| ChannelStore.Get | p99 | 361ms | 367ms | 6ms | 1.66
| ThreadStore.GetTotalThreads | p99 | 774ms | 786ms | 12ms | 1.55
| TeamStore.GetTeamsByUserId | p99 | 649ms | 659ms | 10ms | 1.54
| ThreadStore.MarkAllAsReadByChannels | p99 | 212ms | 215ms | 3ms | 1.42
| TeamStore.GetAllPage | p99 | 665ms | 674ms | 9ms | 1.35
| PostAcknowledgementStore.GetForPost | p99 | 765ms | 774ms | 9ms | 1.18
| JobStore.UpdateStatusOptimistically | p99 | 173ms | 175ms | 2ms | 1.15
| ChannelStore.GetByName | p99 | 563ms | 569ms | 6ms | 1.07
| JobStore.GetAllByStatus | p99 | 884ms | 893ms | 9ms | 1.02
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| FileInfoStore.DeleteForPost | avg | 69ms | 21ms | -48ms | -69.75
| PostStore.GetPostReminders | avg | 65ms | 35ms | -30ms | -46.12
| CommandWebhookStore.Cleanup | avg | 21ms | 12ms | -9ms | -43.18
| StatusStore.SaveOrUpdate | avg | 78ms | 47ms | -31ms | -39.99
| BotStore.Get | avg | 100ms | 62ms | -38ms | -37.88
| JobStore.Save | avg | 30ms | 20ms | -10ms | -32.80
| StatusStore.UpdateExpiredDNDStatuses | avg | 65ms | 54ms | -11ms | -16.95
| PostStore.GetPostReminderMetadata | avg | 75ms | 65ms | -10ms | -13.26
| PostStore.SetPostReminder | avg | 68ms | 61ms | -7ms | -10.36
| FileInfoStore.AttachToPost | avg | 39ms | 35ms | -4ms | -10.28
| SessionStore.Remove | avg | 22ms | 20ms | -2ms | -9.29
| UserStore.GetByUsername | avg | 95ms | 87ms | -8ms | -8.45
| JobStore.Get | avg | 72ms | 66ms | -6ms | -8.31
| PreferenceStore.DeleteCategoryAndName | avg | 37ms | 34ms | -3ms | -8.09
| FileInfoStore.Save | avg | 29ms | 27ms | -2ms | -6.95
| ClusterDiscoveryStore.SetLastPingAt | avg | 32ms | 30ms | -2ms | -6.25
| ThreadStore.MarkAllAsReadByTeam | avg | 33ms | 31ms | -2ms | -6.04
| PostStore.SearchPostsForUser | avg | 234ms | 220ms | -14ms | -5.99
| ChannelStore.GetFileCount | avg | 69ms | 65ms | -4ms | -5.81
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 40ms | 38ms | -2ms | -5.04
| TeamStore.GetByName | avg | 67ms | 64ms | -3ms | -4.47
| TeamStore.AnalyticsTeamCount | avg | 47ms | 45ms | -2ms | -4.30
| ThreadStore.MaintainMembership | avg | 47ms | 45ms | -2ms | -4.27
| ChannelStore.UpdateSidebarCategories | avg | 375ms | 360ms | -15ms | -4.00
| ReactionStore.Save | avg | 75ms | 72ms | -3ms | -3.99
| SessionStore.GetSessionsWithActiveDeviceIds | avg | 59ms | 57ms | -2ms | -3.40
| PostStore.Save | avg | 69ms | 67ms | -2ms | -2.90
| PostAcknowledgementStore.GetForPost | avg | 70ms | 68ms | -2ms | -2.88
| ChannelStore.GetMemberCount | avg | 79ms | 77ms | -2ms | -2.55
| ChannelStore.GetMembers | avg | 121ms | 118ms | -3ms | -2.48
| UserStore.GetProfilesInChannel | avg | 86ms | 84ms | -2ms | -2.33
| ChannelStore.CreateSidebarCategory | avg | 172ms | 169ms | -3ms | -1.74
| UserStore.InvalidateProfilesInChannelCacheByUser | avg | 332ms | 327ms | -5ms | -1.51
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| CommandWebhookStore.Cleanup | p99 | 96ms | 25ms | -71ms | -73.96
| BotStore.Get | p99 | 870ms | 365ms | -505ms | -58.05
| FileInfoStore.DeleteForPost | p99 | 476ms | 211ms | -265ms | -55.64
| StatusStore.SaveOrUpdate | p99 | 1.795s | 855ms | -940ms | -52.38
| JobStore.GetCountByStatusAndType | p99 | 867ms | 431ms | -436ms | -50.26
| TokenStore.Cleanup | p99 | 96ms | 48ms | -48ms | -50.00
| PostStore.GetPostReminders | p99 | 457ms | 234ms | -223ms | -48.83
| SessionStore.GetSessionsExpired | p99 | 445ms | 241ms | -204ms | -45.84
| JobStore.Get | p99 | 760ms | 458ms | -302ms | -39.74
| PostStore.Delete | p99 | 1.47s | 989ms | -481ms | -32.72
| JobStore.Save | p99 | 231ms | 169ms | -62ms | -26.90
| TeamStore.AnalyticsTeamCount | p99 | 641ms | 523ms | -118ms | -18.40
| ChannelStore.GetFileCount | p99 | 781ms | 681ms | -100ms | -12.80
| FileInfoStore.AttachToPost | p99 | 301ms | 269ms | -32ms | -10.64
| PostStore.GetPostReminderMetadata | p99 | 497ms | 454ms | -43ms | -8.65
| ClusterDiscoveryStore.SetLastPingAt | p99 | 249ms | 230ms | -19ms | -7.64
| ChannelStore.GetChannelUnread | p99 | 735ms | 686ms | -49ms | -6.67
| ChannelStore.GetSidebarCategory | p99 | 968ms | 907ms | -61ms | -6.30
| ThreadStore.Get | p99 | 892ms | 839ms | -53ms | -5.94
| PostStore.SearchPostsForUser | p99 | 1.653s | 1.56s | -93ms | -5.63
| PreferenceStore.GetAll | p99 | 712ms | 674ms | -38ms | -5.34
| StatusStore.UpdateExpiredDNDStatuses | p99 | 457ms | 433ms | -24ms | -5.26
| UserStore.UpdateUpdateAt | p99 | 180ms | 172ms | -8ms | -4.44
| TeamStore.GetMember | p99 | 722ms | 691ms | -31ms | -4.29
| SessionStore.Remove | p99 | 190ms | 182ms | -8ms | -4.22
| ChannelStore.UpdateSidebarChannelsByPreferences | p99 | 190ms | 182ms | -8ms | -4.20
| UserStore.InvalidateProfilesInChannelCacheByUser | p99 | 2.045s | 1.973s | -72ms | -3.52
| UserStore.GetAllProfiles | p99 | 865ms | 835ms | -30ms | -3.47
| EmojiStore.GetMultipleByName | p99 | 674ms | 651ms | -23ms | -3.41
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 738ms | 713ms | -25ms | -3.39
| FileInfoStore.Save | p99 | 238ms | 230ms | -8ms | -3.36
| UserStore.GetByUsername | p99 | 906ms | 877ms | -29ms | -3.20
| ChannelStore.SaveMember | p99 | 1.809s | 1.755s | -54ms | -2.98
| SessionStore.UpdateLastActivityAt | p99 | 210ms | 204ms | -6ms | -2.86
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 777ms | 755ms | -22ms | -2.83
| PostStore.GetPostsByThread | p99 | 890ms | 865ms | -25ms | -2.81
| TeamStore.Get | p99 | 738ms | 718ms | -20ms | -2.71
| LinkMetadataStore.Get | p99 | 675ms | 657ms | -18ms | -2.67
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 435ms | 424ms | -11ms | -2.53
| ChannelStore.UpdateLastViewedAt | p99 | 298ms | 291ms | -7ms | -2.35
| PluginStore.Delete | p99 | 174ms | 170ms | -4ms | -2.30
| ThreadStore.GetThreadFollowers | p99 | 832ms | 813ms | -19ms | -2.28
| WebhookStore.GetOutgoingByTeam | p99 | 839ms | 820ms | -19ms | -2.26
| UserStore.UpdateFailedPasswordAttempts | p99 | 222ms | 217ms | -5ms | -2.25
| ChannelStore.GetChannels | p99 | 876ms | 857ms | -19ms | -2.17
| JobStore.GetNewestJobByStatusesAndType | p99 | 970ms | 950ms | -20ms | -2.06
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 2.078s | 2.036s | -42ms | -2.02
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 201ms | 197ms | -4ms | -1.99
| ReactionStore.Save | p99 | 473ms | 464ms | -9ms | -1.90
| ThreadStore.GetThreadUnreadReplyCount | p99 | 908ms | 892ms | -16ms | -1.76
| StatusStore.UpdateLastActivityAt | p99 | 227ms | 223ms | -4ms | -1.76
| JobStore.UpdateStatus | p99 | 178ms | 175ms | -3ms | -1.69
| ThreadStore.MaintainMembership | p99 | 391ms | 385ms | -6ms | -1.53
| ThreadStore.MarkAsRead | p99 | 197ms | 194ms | -3ms | -1.52
| UserStore.GetProfilesInChannel | p99 | 856ms | 843ms | -13ms | -1.52
| PostStore.Get | p99 | 1.857s | 1.829s | -28ms | -1.51
| LinkMetadataStore.Save | p99 | 209ms | 206ms | -3ms | -1.44
| ThreadStore.UpdateMembership | p99 | 213ms | 210ms | -3ms | -1.41
| PostStore.GetPostIdBeforeTime | p99 | 216ms | 213ms | -3ms | -1.39
| PreferenceStore.Save | p99 | 460ms | 454ms | -6ms | -1.30
| ChannelStore.CreateSidebarCategory | p99 | 937ms | 925ms | -12ms | -1.28
| PostStore.Save | p99 | 489ms | 483ms | -6ms | -1.23
| PostPersistentNotificationStore.GetSingle | p99 | 847ms | 837ms | -10ms | -1.18
| ChannelStore.GetMembersForUser | p99 | 850ms | 840ms | -10ms | -1.18
| ThreadStore.GetTotalUnreadThreads | p99 | 778ms | 769ms | -9ms | -1.16
| PostPriorityStore.GetForPosts | p99 | 918ms | 908ms | -10ms | -1.09
| PostAcknowledgementStore.GetForPosts | p99 | 920ms | 910ms | -10ms | -1.09
| UserStore.IsEmpty | p99 | 390ms | 386ms | -4ms | -1.03
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getTopThreadsForUserSince | avg | 99ms | 120ms | 21ms | 21.19
| createChannel | avg | 169ms | 182ms | 13ms | 7.70
| getChannelsForUser | avg | 70ms | 74ms | 4ms | 5.72
| autocompleteChannelsForTeamForSearch | avg | 421ms | 445ms | 24ms | 5.70
| getChannelMember | avg | 58ms | 61ms | 3ms | 5.15
| getChannelMembers | avg | 119ms | 125ms | 6ms | 5.06
| getTeamMembersForUser | avg | 64ms | 67ms | 3ms | 4.69
| getChannel | avg | 136ms | 142ms | 6ms | 4.40
| searchUsers | avg | 284ms | 296ms | 12ms | 4.22
| searchGroupChannels | avg | 99ms | 103ms | 4ms | 4.03
| searchAllChannels | avg | 461ms | 479ms | 18ms | 3.91
| autocompleteUsers | avg | 433ms | 449ms | 16ms | 3.69
| getTeamsForUser | avg | 62ms | 64ms | 2ms | 3.23
| getAllTeams | avg | 65ms | 67ms | 2ms | 3.09
| getPostsForChannelAroundLastUnread | avg | 699ms | 720ms | 21ms | 3.00
| getCategoriesForTeamForUser | avg | 208ms | 214ms | 6ms | 2.88
| getFilePreview | avg | 177ms | 182ms | 5ms | 2.82
| getTeamsUnreadForUser | avg | 118ms | 121ms | 3ms | 2.54
| getUsersByNames | avg | 79ms | 81ms | 2ms | 2.54
| getChannelMembersForTeamForUser | avg | 83ms | 85ms | 2ms | 2.40
| getChannelsForTeamForUser | avg | 90ms | 92ms | 2ms | 2.23
| login | avg | 496ms | 506ms | 10ms | 2.01
| getThreadsForUser | avg | 101ms | 103ms | 2ms | 1.99
| getFileThumbnail | avg | 161ms | 164ms | 3ms | 1.87
| getPostThread | avg | 536ms | 546ms | 10ms | 1.87
| saveReaction | avg | 337ms | 342ms | 5ms | 1.49
| viewChannel | avg | 373ms | 378ms | 5ms | 1.34
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getTopThreadsForUserSince | p99 | 854ms | 1.458s | 604ms | 70.75
| deletePost | p99 | 3.161s | 3.632s | 471ms | 14.90
| getChannelMember | p99 | 573ms | 615ms | 42ms | 7.33
| getChannel | p99 | 1.169s | 1.247s | 78ms | 6.67
| getChannelMembers | p99 | 974ms | 1.03s | 56ms | 5.75
| getChannelsForUser | p99 | 706ms | 733ms | 27ms | 3.83
| getUsersByIds | p99 | 160ms | 166ms | 6ms | 3.76
| getUserStatusesByIds | p99 | 214ms | 220ms | 6ms | 2.81
| followThreadByUser | p99 | 1.91s | 1.963s | 53ms | 2.78
| searchAllChannels | p99 | 8.067s | 8.278s | 211ms | 2.62
| getTeamsForUser | p99 | 656ms | 670ms | 14ms | 2.14
| getPostsForChannelAroundLastUnread | p99 | 7.452s | 7.592s | 140ms | 1.88
| searchUsers | p99 | 2.089s | 2.127s | 38ms | 1.82
| getTeamMembersForUser | p99 | 697ms | 707ms | 10ms | 1.43
| getAllTeams | p99 | 700ms | 708ms | 8ms | 1.14
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| setPostReminder | avg | 476ms | 360ms | -116ms | -24.37
| getProfileImage | avg | 86ms | 78ms | -8ms | -9.26
| patchPost | avg | 1.149s | 1.044s | -105ms | -9.14
| updateReadStateAllThreadsByUser | avg | 34ms | 31ms | -3ms | -8.83
| searchPostsInTeam | avg | 703ms | 677ms | -26ms | -3.70
| updatePreferences | avg | 89ms | 86ms | -3ms | -3.36
| updateCategoriesForTeamForUser | avg | 725ms | 701ms | -24ms | -3.31
| logout | avg | 411ms | 399ms | -12ms | -2.92
| updateUserCustomStatus | avg | 714ms | 696ms | -18ms | -2.52
| createGroupChannel | avg | 1.765s | 1.722s | -43ms | -2.44
| getUsers | avg | 126ms | 123ms | -3ms | -2.38
| createDirectChannel | avg | 950ms | 929ms | -21ms | -2.21
| removeUserCustomStatus | avg | 564ms | 554ms | -10ms | -1.77
| unfollowThreadByUser | avg | 267ms | 263ms | -4ms | -1.50
| uploadFileStream | avg | 661ms | 654ms | -7ms | -1.06
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| setPostReminder | p99 | 3.642s | 2.295s | -1.347s | -36.99
| getUsers | p99 | 1.19s | 998ms | -192ms | -16.14
| patchPost | p99 | 5.733s | 4.853s | -880ms | -15.35
| updateCategoriesForTeamForUser | p99 | 4.076s | 3.687s | -389ms | -9.54
| createGroupChannel | p99 | 7.873s | 7.288s | -585ms | -7.43
| getPreferences | p99 | 733ms | 695ms | -38ms | -5.18
| createCategoryForTeamForUser | p99 | 1.824s | 1.731s | -93ms | -5.10
| addChannelMember | p99 | 6.878s | 6.614s | -264ms | -3.84
| createDirectChannel | p99 | 4.234s | 4.076s | -158ms | -3.73
| getFileThumbnail | p99 | 1.166s | 1.125s | -41ms | -3.52
| createUser | p99 | 2.08s | 2.016s | -64ms | -3.08
| unfollowThreadByUser | p99 | 2.085s | 2.025s | -60ms | -2.88
| logout | p99 | 2.23s | 2.174s | -56ms | -2.51
| updateReadStateThreadByUser | p99 | 4.544s | 4.442s | -102ms | -2.24
| getProfileImage | p99 | 493ms | 482ms | -11ms | -2.23
| getChannelsForTeamForUser | p99 | 878ms | 859ms | -19ms | -2.16
| searchPostsInTeam | p99 | 10s | 9.797s | -203ms | -2.03
| getPostThread | p99 | 4.177s | 4.093s | -84ms | -2.01
| getUser | p99 | 918ms | 900ms | -18ms | -1.96
| getCategoriesForTeamForUser | p99 | 2.078s | 2.039s | -39ms | -1.88
| login | p99 | 2.53s | 2.485s | -45ms | -1.78
| getFilePreview | p99 | 1.271s | 1.253s | -18ms | -1.42
| getChannelMembersForTeamForUser | p99 | 854ms | 842ms | -12ms | -1.40
| removeUserCustomStatus | p99 | 2.404s | 2.373s | -31ms | -1.29
| updateReadStateAllThreadsByUser | p99 | 243ms | 240ms | -3ms | -1.24
| getChannelUnread | p99 | 891ms | 880ms | -11ms | -1.23
| updatePreferences | p99 | 493ms | 487ms | -6ms | -1.22
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 23ms| 23ms | 0s | 0.000
| |  P99| 223ms| 221ms | -2ms | -0.898
| BotStore.Get |  Avg| 100ms| 62ms | -38ms | -37.879
| |  P99| 870ms| 365ms | -505ms | -58.046
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 20ms| 19ms | -1ms | -5.085
| |  P99| 201ms| 197ms | -4ms | -1.986
| ChannelStore.Autocomplete |  Avg| 458ms| 477ms | 19ms | 4.145
| |  P99| 8.065s| 8.277s | 212ms | 2.629
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 420ms| 444ms | 24ms | 5.713
| |  P99| 2.451s| 2.458s | 7ms | 0.286
| ChannelStore.CreateDirectChannel |  Avg| 152ms| 151ms | -1ms | -0.658
| |  P99| 944ms| 935ms | -9ms | -0.953
| ChannelStore.CreateInitialSidebarCategories |  Avg| 135ms| 135ms | 0s | 0.000
| |  P99| 945ms| 937ms | -8ms | -0.847
| ChannelStore.CreateSidebarCategory |  Avg| 172ms| 169ms | -3ms | -1.742
| |  P99| 937ms| 925ms | -12ms | -1.281
| ChannelStore.Get |  Avg| 17ms| 17ms | 0s | 0.000
| |  P99| 361ms| 367ms | 6ms | 1.663
| ChannelStore.GetAllChannelMembersForUser |  Avg| 24ms| 25ms | 1ms | 4.137
| |  P99| 429ms| 429ms | 0s | 0.000
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 40ms| 38ms | -2ms | -5.037
| |  P99| 435ms| 424ms | -11ms | -2.527
| ChannelStore.GetByName |  Avg| 52ms| 52ms | 0s | 0.000
| |  P99| 563ms| 569ms | 6ms | 1.065
| ChannelStore.GetChannelUnread |  Avg| 65ms| 65ms | 0s | 0.000
| |  P99| 735ms| 686ms | -49ms | -6.667
| ChannelStore.GetChannels |  Avg| 89ms| 91ms | 2ms | 2.252
| |  P99| 876ms| 857ms | -19ms | -2.169
| ChannelStore.GetChannelsByUser |  Avg| 69ms| 73ms | 4ms | 5.772
| |  P99| 701ms| 729ms | 28ms | 3.992
| ChannelStore.GetFileCount |  Avg| 69ms| 65ms | -4ms | -5.811
| |  P99| 781ms| 681ms | -100ms | -12.804
| ChannelStore.GetGuestCount |  Avg| 30ms| 31ms | 1ms | 3.322
| |  P99| 460ms| 459ms | -1ms | -0.217
| ChannelStore.GetMember |  Avg| 33ms| 36ms | 3ms | 9.171
| |  P99| 463ms| 474ms | 11ms | 2.378
| ChannelStore.GetMemberCount |  Avg| 79ms| 77ms | -2ms | -2.547
| |  P99| 922ms| 924ms | 2ms | 0.217
| ChannelStore.GetMemberForPost |  Avg| 57ms| 59ms | 2ms | 3.497
| |  P99| 652ms| 650ms | -2ms | -0.307
| ChannelStore.GetMembers |  Avg| 121ms| 118ms | -3ms | -2.480
| |  P99| 1.263s| 1.292s | 29ms | 2.296
| ChannelStore.GetMembersForUser |  Avg| 82ms| 84ms | 2ms | 2.432
| |  P99| 850ms| 840ms | -10ms | -1.176
| ChannelStore.GetPinnedPostCount |  Avg| 40ms| 41ms | 1ms | 2.517
| |  P99| 497ms| 494ms | -3ms | -0.604
| ChannelStore.GetPublicChannelsForTeam |  Avg| 112ms| 113ms | 1ms | 0.894
| |  P99| 909ms| 902ms | -7ms | -0.770
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 207ms| 213ms | 6ms | 2.892
| |  P99| 2.078s| 2.036s | -42ms | -2.021
| ChannelStore.GetSidebarCategory |  Avg| 131ms| 130ms | -1ms | -0.762
| |  P99| 968ms| 907ms | -61ms | -6.300
| ChannelStore.GetTeamChannels |  Avg| 168ms| 181ms | 13ms | 7.736
| |  P99| 971ms| 974ms | 3ms | 0.309
| ChannelStore.IncrementMentionCount |  Avg| 20ms| 20ms | 0s | 0.000
| |  P99| 216ms| 215ms | -1ms | -0.462
| ChannelStore.InvalidateAllChannelMembersForUser |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.InvalidateChannel |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.InvalidateChannelByName |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.InvalidateGuestCount |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.InvalidateMemberCount |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.InvalidatePinnedPostCount |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.Save |  Avg| 127ms| 128ms | 1ms | 0.787
| |  P99| 890ms| 906ms | 16ms | 1.797
| ChannelStore.SaveMember |  Avg| 208ms| 209ms | 1ms | 0.482
| |  P99| 1.809s| 1.755s | -54ms | -2.984
| ChannelStore.SearchGroupChannels |  Avg| 99ms| 103ms | 4ms | 4.059
| |  P99| 903ms| 908ms | 5ms | 0.554
| ChannelStore.UpdateLastViewedAt |  Avg| 40ms| 39ms | -1ms | -2.501
| |  P99| 298ms| 291ms | -7ms | -2.346
| ChannelStore.UpdateSidebarCategories |  Avg| 375ms| 360ms | -15ms | -3.997
| |  P99| 2.328s| 2.319s | -9ms | -0.387
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 18ms| 18ms | 0s | 0.000
| |  P99| 190ms| 182ms | -8ms | -4.201
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 32ms| 30ms | -2ms | -6.251
| |  P99| 249ms| 230ms | -19ms | -7.638
| CommandWebhookStore.Cleanup |  Avg| 21ms| 12ms | -9ms | -43.177
| |  P99| 96ms| 25ms | -71ms | -73.958
| EmojiStore.GetMultipleByName |  Avg| 53ms| 53ms | 0s | 0.000
| |  P99| 674ms| 651ms | -23ms | -3.413
| FileInfoStore.AttachToPost |  Avg| 39ms| 35ms | -4ms | -10.278
| |  P99| 301ms| 269ms | -32ms | -10.638
| FileInfoStore.DeleteForPost |  Avg| 69ms| 21ms | -48ms | -69.752
| |  P99| 476ms| 211ms | -265ms | -55.643
| FileInfoStore.Get |  Avg| 61ms| 63ms | 2ms | 3.303
| |  P99| 668ms| 672ms | 4ms | 0.599
| FileInfoStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.InvalidateFileInfosForPostCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.Save |  Avg| 29ms| 27ms | -2ms | -6.949
| |  P99| 238ms| 230ms | -8ms | -3.360
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 60ms| 61ms | 1ms | 1.680
| |  P99| 716ms| 717ms | 1ms | 0.140
| GroupStore.GetByName |  Avg| 41ms| 41ms | 0s | 0.000
| |  P99| 470ms| 472ms | 2ms | 0.426
| GroupStore.GetGroups |  Avg| 74ms| 76ms | 2ms | 2.709
| |  P99| 845ms| 852ms | 7ms | 0.828
| JobStore.Get |  Avg| 72ms| 66ms | -6ms | -8.312
| |  P99| 760ms| 458ms | -302ms | -39.738
| JobStore.GetAllByStatus |  Avg| 86ms| 85ms | -1ms | -1.163
| |  P99| 884ms| 893ms | 9ms | 1.018
| JobStore.GetCountByStatusAndType |  Avg| 73ms| 76ms | 3ms | 4.082
| |  P99| 867ms| 431ms | -436ms | -50.259
| JobStore.GetNewestJobByStatusesAndType |  Avg| 62ms| 87ms | 25ms | 40.413
| |  P99| 970ms| 950ms | -20ms | -2.062
| JobStore.Save |  Avg| 30ms| 20ms | -10ms | -32.796
| |  P99| 231ms| 169ms | -62ms | -26.898
| JobStore.UpdateOptimistically |  Avg| 19ms| 20ms | 1ms | 5.361
| |  P99| 94ms| 175ms | 81ms | 86.170
| JobStore.UpdateStatus |  Avg| 16ms| 18ms | 2ms | 12.130
| |  P99| 178ms| 175ms | -3ms | -1.685
| JobStore.UpdateStatusOptimistically |  Avg| 21ms| 23ms | 2ms | 9.680
| |  P99| 173ms| 175ms | 2ms | 1.153
| LinkMetadataStore.Get |  Avg| 53ms| 53ms | 0s | 0.000
| |  P99| 675ms| 657ms | -18ms | -2.666
| LinkMetadataStore.Save |  Avg| 18ms| 18ms | 0s | 0.000
| |  P99| 209ms| 206ms | -3ms | -1.437
| PluginStore.Delete |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 174ms| 170ms | -4ms | -2.301
| PluginStore.List |  Avg| 89ms| 102ms | 13ms | 14.598
| |  P99| 980ms| 983ms | 3ms | 0.306
| PluginStore.SetWithOptions |  Avg| 32ms| 31ms | -1ms | -3.159
| |  P99| 253ms| 252ms | -1ms | -0.396
| PostAcknowledgementStore.GetForPost |  Avg| 70ms| 68ms | -2ms | -2.877
| |  P99| 765ms| 774ms | 9ms | 1.177
| PostAcknowledgementStore.GetForPosts |  Avg| 71ms| 71ms | 0s | 0.000
| |  P99| 920ms| 910ms | -10ms | -1.087
| PostPersistentNotificationStore.GetSingle |  Avg| 75ms| 77ms | 2ms | 2.674
| |  P99| 847ms| 837ms | -10ms | -1.181
| PostPriorityStore.GetForPost |  Avg| 70ms| 78ms | 8ms | 11.448
| |  P99| 790ms| 847ms | 57ms | 7.215
| PostPriorityStore.GetForPosts |  Avg| 71ms| 72ms | 1ms | 1.402
| |  P99| 918ms| 908ms | -10ms | -1.090
| PostStore.AnalyticsPostCount |  Avg| 6.834s| 8.774s | 1.94s | 28.386
| |  P99| 9.95s| 10s | 50ms | 0.503
| PostStore.Delete |  Avg| 179ms| 179ms | 0s | 0.000
| |  P99| 1.47s| 989ms | -481ms | -32.722
| PostStore.Get |  Avg| 184ms| 186ms | 2ms | 1.089
| |  P99| 1.857s| 1.829s | -28ms | -1.508
| PostStore.GetEtag |  Avg| 36ms| 37ms | 1ms | 2.794
| |  P99| 492ms| 490ms | -2ms | -0.406
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 20ms| 20ms | 0s | 0.000
| |  P99| 211ms| 209ms | -2ms | -0.947
| PostStore.GetPostIdBeforeTime |  Avg| 21ms| 21ms | 0s | 0.000
| |  P99| 216ms| 213ms | -3ms | -1.391
| PostStore.GetPostReminderMetadata |  Avg| 75ms| 65ms | -10ms | -13.259
| |  P99| 497ms| 454ms | -43ms | -8.650
| PostStore.GetPostReminders |  Avg| 65ms| 35ms | -30ms | -46.119
| |  P99| 457ms| 234ms | -223ms | -48.832
| PostStore.GetPosts |  Avg| 67ms| 68ms | 1ms | 1.501
| |  P99| 758ms| 761ms | 3ms | 0.396
| PostStore.GetPostsAfter |  Avg| 80ms| 82ms | 2ms | 2.510
| |  P99| 867ms| 870ms | 3ms | 0.346
| PostStore.GetPostsBefore |  Avg| 93ms| 95ms | 2ms | 2.145
| |  P99| 908ms| 905ms | -3ms | -0.330
| PostStore.GetPostsByThread |  Avg| 79ms| 80ms | 1ms | 1.266
| |  P99| 890ms| 865ms | -25ms | -2.810
| PostStore.GetPostsSince |  Avg| 123ms| 128ms | 5ms | 4.055
| |  P99| 930ms| 935ms | 5ms | 0.537
| PostStore.GetSingle |  Avg| 73ms| 74ms | 1ms | 1.378
| |  P99| 834ms| 829ms | -5ms | -0.599
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 69ms| 67ms | -2ms | -2.898
| |  P99| 489ms| 483ms | -6ms | -1.228
| PostStore.SearchPostsForUser |  Avg| 234ms| 220ms | -14ms | -5.990
| |  P99| 1.653s| 1.56s | -93ms | -5.626
| PostStore.SetPostReminder |  Avg| 68ms| 61ms | -7ms | -10.364
| |  P99| 432ms| 468ms | 36ms | 8.332
| PostStore.Update |  Avg| 73ms| 72ms | -1ms | -1.372
| |  P99| 452ms| 460ms | 8ms | 1.770
| PreferenceStore.DeleteCategoryAndName |  Avg| 37ms| 34ms | -3ms | -8.087
| |  P99| 395ms| 418ms | 23ms | 5.823
| PreferenceStore.Get |  Avg| 67ms| 68ms | 1ms | 1.496
| |  P99| 784ms| 778ms | -6ms | -0.766
| PreferenceStore.GetAll |  Avg| 67ms| 68ms | 1ms | 1.498
| |  P99| 712ms| 674ms | -38ms | -5.339
| PreferenceStore.Save |  Avg| 66ms| 65ms | -1ms | -1.505
| |  P99| 460ms| 454ms | -6ms | -1.304
| ProductNoticesStore.ClearOldNotices |  Avg| 3ms| 6ms | 3ms | 85.970
| |  P99| 10ms| 24ms | 14ms | 142.857
| ProductNoticesStore.View |  Avg| 122ms| 124ms | 2ms | 1.636
| |  P99| 887ms| 881ms | -6ms | -0.677
| ReactionStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.017
| ReactionStore.Save |  Avg| 75ms| 72ms | -3ms | -3.985
| |  P99| 473ms| 464ms | -9ms | -1.903
| RoleStore.ChannelHigherScopedPermissions |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| RoleStore.GetByNames |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Get |  Avg| 43ms| 43ms | 0s | 0.000
| |  P99| 411ms| 411ms | 0s | 0.000
| SessionStore.GetSessionsExpired |  Avg| 42ms| 55ms | 13ms | 30.722
| |  P99| 445ms| 241ms | -204ms | -45.843
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 59ms| 57ms | -2ms | -3.403
| |  P99| 738ms| 713ms | -25ms | -3.386
| SessionStore.Remove |  Avg| 22ms| 20ms | -2ms | -9.294
| |  P99| 190ms| 182ms | -8ms | -4.221
| SessionStore.Save |  Avg| 74ms| 77ms | 3ms | 4.054
| |  P99| 741ms| 754ms | 13ms | 1.754
| SessionStore.UpdateLastActivityAt |  Avg| 22ms| 21ms | -1ms | -4.490
| |  P99| 210ms| 204ms | -6ms | -2.860
| StatusStore.Get |  Avg| 40ms| 40ms | 0s | 0.000
| |  P99| 477ms| 475ms | -2ms | -0.419
| StatusStore.GetByIds |  Avg| 109ms| 111ms | 2ms | 1.841
| |  P99| 966ms| 965ms | -1ms | -0.104
| StatusStore.SaveOrUpdate |  Avg| 78ms| 47ms | -31ms | -39.985
| |  P99| 1.795s| 855ms | -940ms | -52.382
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 65ms| 54ms | -11ms | -16.948
| |  P99| 457ms| 433ms | -24ms | -5.255
| StatusStore.UpdateLastActivityAt |  Avg| 26ms| 25ms | -1ms | -3.900
| |  P99| 227ms| 223ms | -4ms | -1.762
| SystemStore.Get |  Avg| 43ms| 113ms | 70ms | 161.591
| |  P99| 99ms| 247ms | 148ms | 149.495
| SystemStore.GetByName |  Avg| 17ms| 17ms | 0s | 0.000
| |  P99| 202ms| 201ms | -1ms | -0.494
| TeamStore.AnalyticsTeamCount |  Avg| 47ms| 45ms | -2ms | -4.296
| |  P99| 641ms| 523ms | -118ms | -18.398
| TeamStore.Get |  Avg| 61ms| 61ms | 0s | 0.000
| |  P99| 738ms| 718ms | -20ms | -2.711
| TeamStore.GetAllPage |  Avg| 61ms| 62ms | 1ms | 1.649
| |  P99| 665ms| 674ms | 9ms | 1.354
| TeamStore.GetByName |  Avg| 67ms| 64ms | -3ms | -4.467
| |  P99| 797ms| 790ms | -7ms | -0.878
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 65ms| 66ms | 1ms | 1.538
| |  P99| 723ms| 725ms | 2ms | 0.277
| TeamStore.GetMember |  Avg| 62ms| 63ms | 1ms | 1.608
| |  P99| 722ms| 691ms | -31ms | -4.292
| TeamStore.GetTeamsByUserId |  Avg| 61ms| 63ms | 2ms | 3.262
| |  P99| 649ms| 659ms | 10ms | 1.541
| TeamStore.GetTeamsForUser |  Avg| 60ms| 63ms | 3ms | 5.004
| |  P99| 662ms| 677ms | 15ms | 2.267
| TeamStore.InvalidateAllTeamIdsForUser |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.SaveMember |  Avg| 124ms| 124ms | 0s | 0.000
| |  P99| 472ms| 471ms | -1ms | -0.212
| ThreadStore.Get |  Avg| 85ms| 84ms | -1ms | -1.181
| |  P99| 892ms| 839ms | -53ms | -5.943
| ThreadStore.GetMembershipForUser |  Avg| 70ms| 72ms | 2ms | 2.858
| |  P99| 824ms| 816ms | -8ms | -0.970
| ThreadStore.GetTeamsUnreadForUser |  Avg| 100ms| 104ms | 4ms | 3.995
| |  P99| 1.094s| 1.117s | 23ms | 2.102
| ThreadStore.GetThreadFollowers |  Avg| 71ms| 75ms | 4ms | 5.641
| |  P99| 832ms| 813ms | -19ms | -2.282
| ThreadStore.GetThreadForUser |  Avg| 98ms| 99ms | 1ms | 1.022
| |  P99| 974ms| 970ms | -4ms | -0.411
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 89ms| 90ms | 1ms | 1.124
| |  P99| 908ms| 892ms | -16ms | -1.763
| ThreadStore.GetThreadsForUser |  Avg| 96ms| 99ms | 3ms | 3.115
| |  P99| 899ms| 891ms | -8ms | -0.890
| ThreadStore.GetTotalThreads |  Avg| 68ms| 71ms | 3ms | 4.402
| |  P99| 774ms| 786ms | 12ms | 1.551
| ThreadStore.GetTotalUnreadMentions |  Avg| 68ms| 70ms | 2ms | 2.956
| |  P99| 761ms| 778ms | 17ms | 2.235
| ThreadStore.GetTotalUnreadThreads |  Avg| 69ms| 71ms | 2ms | 2.905
| |  P99| 778ms| 769ms | -9ms | -1.157
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 69ms| 70ms | 1ms | 1.444
| |  P99| 777ms| 755ms | -22ms | -2.832
| ThreadStore.MaintainMembership |  Avg| 47ms| 45ms | -2ms | -4.272
| |  P99| 391ms| 385ms | -6ms | -1.534
| ThreadStore.MarkAllAsReadByChannels |  Avg| 21ms| 21ms | 0s | 0.000
| |  P99| 212ms| 215ms | 3ms | 1.416
| ThreadStore.MarkAllAsReadByTeam |  Avg| 33ms| 31ms | -2ms | -6.043
| |  P99| 239ms| 240ms | 1ms | 0.419
| ThreadStore.MarkAsRead |  Avg| 21ms| 20ms | -1ms | -4.720
| |  P99| 197ms| 194ms | -3ms | -1.523
| ThreadStore.UpdateMembership |  Avg| 23ms| 22ms | -1ms | -4.311
| |  P99| 213ms| 210ms | -3ms | -1.411
| TokenStore.Cleanup |  Avg| 18ms| 17ms | -1ms | -5.703
| |  P99| 96ms| 48ms | -48ms | -50.000
| UserAccessTokenStore.GetByToken |  Avg| 82ms| 87ms | 5ms | 6.114
| |  P99| 823ms| 900ms | 77ms | 9.352
| UserStore.AutocompleteUsersInChannel |  Avg| 637ms| 663ms | 26ms | 4.083
| |  P99| 2.401s| 2.406s | 5ms | 0.208
| UserStore.Count |  Avg| 187ms| 226ms | 39ms | 20.849
| |  P99| 492ms| 495ms | 3ms | 0.610
| UserStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 47ms| 48ms | 1ms | 2.126
| UserStore.GetAllProfiles |  Avg| 75ms| 74ms | -1ms | -1.333
| |  P99| 865ms| 835ms | -30ms | -3.466
| UserStore.GetAllProfilesInChannel |  Avg| 774ms| 771ms | -3ms | -0.388
| |  P99| 4.775s| 4.797s | 22ms | 0.461
| UserStore.GetByUsername |  Avg| 95ms| 87ms | -8ms | -8.451
| |  P99| 906ms| 877ms | -29ms | -3.203
| UserStore.GetForLogin |  Avg| 54ms| 56ms | 2ms | 3.684
| |  P99| 608ms| 612ms | 4ms | 0.658
| UserStore.GetMany |  Avg| 8ms| 7ms | -1ms | -12.929
| |  P99| 156ms| 156ms | 0s | 0.000
| UserStore.GetProfileByIds |  Avg| 3ms| 4ms | 1ms | 30.415
| |  P99| 94ms| 99ms | 5ms | 5.327
| UserStore.GetProfilesByUsernames |  Avg| 78ms| 80ms | 2ms | 2.576
| |  P99| 814ms| 810ms | -4ms | -0.492
| UserStore.GetProfilesInChannel |  Avg| 86ms| 84ms | -2ms | -2.327
| |  P99| 856ms| 843ms | -13ms | -1.519
| UserStore.GetUnreadCount |  Avg| 64ms| 65ms | 1ms | 1.561
| |  P99| 687ms| 761ms | 74ms | 10.768
| UserStore.GetUnreadCountForChannel |  Avg| 68ms| 70ms | 2ms | 2.930
| |  P99| 781ms| 780ms | -1ms | -0.128
| UserStore.InvalidateProfileCacheForUser |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.InvalidateProfilesInChannelCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.InvalidateProfilesInChannelCacheByUser |  Avg| 332ms| 327ms | -5ms | -1.508
| |  P99| 2.045s| 1.973s | -72ms | -3.521
| UserStore.IsEmpty |  Avg| 26ms| 25ms | -1ms | -3.869
| |  P99| 390ms| 386ms | -4ms | -1.025
| UserStore.Save |  Avg| 122ms| 123ms | 1ms | 0.821
| |  P99| 498ms| 495ms | -3ms | -0.602
| UserStore.Search |  Avg| 273ms| 285ms | 12ms | 4.395
| |  P99| 2.055s| 2.099s | 44ms | 2.141
| UserStore.Update |  Avg| 55ms| 54ms | -1ms | -1.812
| |  P99| 400ms| 398ms | -2ms | -0.501
| UserStore.UpdateFailedPasswordAttempts |  Avg| 23ms| 23ms | 0s | 0.000
| |  P99| 222ms| 217ms | -5ms | -2.254
| UserStore.UpdateUpdateAt |  Avg| 17ms| 17ms | 0s | 0.000
| |  P99| 180ms| 172ms | -8ms | -4.438
| UserTermsOfServiceStore.GetByUser |  Avg| 62ms| 63ms | 1ms | 1.619
| |  P99| 700ms| 699ms | -1ms | -0.143
| WebhookStore.GetOutgoingByTeam |  Avg| 77ms| 78ms | 1ms | 1.299
| |  P99| 839ms| 820ms | -19ms | -2.265
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 1.47s| 1.474s | 4ms | 0.272
| | P99| 6.878s| 6.614s | -264ms | -3.838
| addTeamMember | Avg| 3.859s| 3.858s | -1ms | -0.026
| | P99| 10s| 10s | 0s | 0.000
| autocompleteChannelsForTeamForSearch | Avg| 421ms| 445ms | 24ms | 5.703
| | P99| 2.451s| 2.462s | 11ms | 0.449
| autocompleteUsers | Avg| 433ms| 449ms | 16ms | 3.693
| | P99| 2.328s| 2.344s | 16ms | 0.687
| createCategoryForTeamForUser | Avg| 274ms| 275ms | 1ms | 0.365
| | P99| 1.824s| 1.731s | -93ms | -5.098
| createChannel | Avg| 169ms| 182ms | 13ms | 7.701
| | P99| 971ms| 974ms | 3ms | 0.309
| createDirectChannel | Avg| 950ms| 929ms | -21ms | -2.209
| | P99| 4.234s| 4.076s | -158ms | -3.732
| createGroupChannel | Avg| 1.765s| 1.722s | -43ms | -2.437
| | P99| 7.873s| 7.288s | -585ms | -7.430
| createPost | Avg| 2.114s| 2.096s | -18ms | -0.851
| | P99| 9.671s| 9.635s | -36ms | -0.372
| createUser | Avg| 297ms| 297ms | 0s | 0.000
| | P99| 2.08s| 2.016s | -64ms | -3.077
| deletePost | Avg| 486ms| 482ms | -4ms | -0.822
| | P99| 3.161s| 3.632s | 471ms | 14.902
| followThreadByUser | Avg| 238ms| 236ms | -2ms | -0.841
| | P99| 1.91s| 1.963s | 53ms | 2.775
| getAllTeams | Avg| 65ms| 67ms | 2ms | 3.085
| | P99| 700ms| 708ms | 8ms | 1.143
| getCategoriesForTeamForUser | Avg| 208ms| 214ms | 6ms | 2.883
| | P99| 2.078s| 2.039s | -39ms | -1.876
| getChannel | Avg| 136ms| 142ms | 6ms | 4.403
| | P99| 1.169s| 1.247s | 78ms | 6.670
| getChannelMember | Avg| 58ms| 61ms | 3ms | 5.150
| | P99| 573ms| 615ms | 42ms | 7.334
| getChannelMembers | Avg| 119ms| 125ms | 6ms | 5.059
| | P99| 974ms| 1.03s | 56ms | 5.749
| getChannelMembersForTeamForUser | Avg| 83ms| 85ms | 2ms | 2.404
| | P99| 854ms| 842ms | -12ms | -1.405
| getChannelStats | Avg| 161ms| 161ms | 0s | 0.000
| | P99| 1.946s| 1.941s | -5ms | -0.257
| getChannelUnread | Avg| 83ms| 84ms | 1ms | 1.202
| | P99| 891ms| 880ms | -11ms | -1.235
| getChannelsForTeamForUser | Avg| 90ms| 92ms | 2ms | 2.225
| | P99| 878ms| 859ms | -19ms | -2.164
| getChannelsForUser | Avg| 70ms| 74ms | 4ms | 5.724
| | P99| 706ms| 733ms | 27ms | 3.827
| getClientConfig | Avg| 50ms| 50ms | 0s | 0.000
| | P99| 447ms| 444ms | -3ms | -0.671
| getFilePreview | Avg| 177ms| 182ms | 5ms | 2.821
| | P99| 1.271s| 1.253s | -18ms | -1.417
| getFileThumbnail | Avg| 161ms| 164ms | 3ms | 1.866
| | P99| 1.166s| 1.125s | -41ms | -3.518
| getPostThread | Avg| 536ms| 546ms | 10ms | 1.865
| | P99| 4.177s| 4.093s | -84ms | -2.011
| getPostsForChannel | Avg| 2.159s| 2.157s | -2ms | -0.093
| | P99| 10s| 10s | 0s | 0.000
| getPostsForChannelAroundLastUnread | Avg| 699ms| 720ms | 21ms | 3.005
| | P99| 7.452s| 7.592s | 140ms | 1.879
| getPreferences | Avg| 69ms| 70ms | 1ms | 1.445
| | P99| 733ms| 695ms | -38ms | -5.183
| getProfileImage | Avg| 86ms| 78ms | -8ms | -9.260
| | P99| 493ms| 482ms | -11ms | -2.232
| getPublicChannelsForTeam | Avg| 115ms| 116ms | 1ms | 0.872
| | P99| 915ms| 907ms | -8ms | -0.875
| getTeamMembersForUser | Avg| 64ms| 67ms | 3ms | 4.686
| | P99| 697ms| 707ms | 10ms | 1.435
| getTeamsForUser | Avg| 62ms| 64ms | 2ms | 3.229
| | P99| 656ms| 670ms | 14ms | 2.135
| getTeamsUnreadForUser | Avg| 118ms| 121ms | 3ms | 2.539
| | P99| 1.475s| 1.482s | 7ms | 0.475
| getThreadsForUser | Avg| 101ms| 103ms | 2ms | 1.986
| | P99| 935ms| 927ms | -8ms | -0.856
| getTopThreadsForTeamSince | Avg| 0s| 0s | 0s | 0.000
| | P99| 6ms| 5ms | -1ms | -15.747
| getTopThreadsForUserSince | Avg| 99ms| 120ms | 21ms | 21.191
| | P99| 854ms| 1.458s | 604ms | 70.754
| getUser | Avg| 95ms| 95ms | 0s | 0.000
| | P99| 918ms| 900ms | -18ms | -1.960
| getUserStatus | Avg| 1ms| 0s | -1ms | -178.820
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 7ms| 8ms | 1ms | 13.434
| | P99| 214ms| 220ms | 6ms | 2.809
| getUsers | Avg| 126ms| 123ms | -3ms | -2.383
| | P99| 1.19s| 998ms | -192ms | -16.139
| getUsersByIds | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 160ms| 166ms | 6ms | 3.760
| getUsersByNames | Avg| 79ms| 81ms | 2ms | 2.537
| | P99| 820ms| 818ms | -2ms | -0.244
| getWebappPlugins | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| login | Avg| 496ms| 506ms | 10ms | 2.015
| | P99| 2.53s| 2.485s | -45ms | -1.779
| logout | Avg| 411ms| 399ms | -12ms | -2.917
| | P99| 2.23s| 2.174s | -56ms | -2.511
| patchPost | Avg| 1.149s| 1.044s | -105ms | -9.135
| | P99| 5.733s| 4.853s | -880ms | -15.349
| removeUserCustomStatus | Avg| 564ms| 554ms | -10ms | -1.772
| | P99| 2.404s| 2.373s | -31ms | -1.289
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 337ms| 342ms | 5ms | 1.486
| | P99| 2.356s| 2.372s | 16ms | 0.679
| searchAllChannels | Avg| 461ms| 479ms | 18ms | 3.906
| | P99| 8.067s| 8.278s | 211ms | 2.616
| searchGroupChannels | Avg| 99ms| 103ms | 4ms | 4.035
| | P99| 904ms| 910ms | 6ms | 0.664
| searchPostsInTeam | Avg| 703ms| 677ms | -26ms | -3.698
| | P99| 10s| 9.797s | -203ms | -2.030
| searchUsers | Avg| 284ms| 296ms | 12ms | 4.224
| | P99| 2.089s| 2.127s | 38ms | 1.819
| setPostReminder | Avg| 476ms| 360ms | -116ms | -24.375
| | P99| 3.642s| 2.295s | -1.347s | -36.988
| unfollowThreadByUser | Avg| 267ms| 263ms | -4ms | -1.500
| | P99| 2.085s| 2.025s | -60ms | -2.878
| updateCategoriesForTeamForUser | Avg| 725ms| 701ms | -24ms | -3.311
| | P99| 4.076s| 3.687s | -389ms | -9.543
| updatePreferences | Avg| 89ms| 86ms | -3ms | -3.362
| | P99| 493ms| 487ms | -6ms | -1.218
| updateReadStateAllThreadsByUser | Avg| 34ms| 31ms | -3ms | -8.828
| | P99| 243ms| 240ms | -3ms | -1.237
| updateReadStateThreadByUser | Avg| 690ms| 693ms | 3ms | 0.435
| | P99| 4.544s| 4.442s | -102ms | -2.245
| updateUserCustomStatus | Avg| 714ms| 696ms | -18ms | -2.522
| | P99| 2.477s| 2.456s | -21ms | -0.848
| uploadFileStream | Avg| 661ms| 654ms | -7ms | -1.058
| | P99| 2.403s| 2.397s | -6ms | -0.250
| viewChannel | Avg| 373ms| 378ms | 5ms | 1.341
| | P99| 2.476s| 2.476s | 0s | 0.000
