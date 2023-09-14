### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| FileInfoStore.DeleteForPost | avg | 25ms | 48ms | 23ms | 92.09
| PluginStore.List | avg | 49ms | 75ms | 26ms | 53.35
| JobStore.UpdateStatus | avg | 24ms | 35ms | 11ms | 45.75
| BotStore.Get | avg | 40ms | 56ms | 16ms | 40.25
| JobStore.GetCountByStatusAndType | avg | 52ms | 70ms | 18ms | 34.89
| PostStore.GetPostReminders | avg | 62ms | 81ms | 19ms | 30.70
| JobStore.UpdateStatusOptimistically | avg | 32ms | 37ms | 5ms | 15.42
| JobStore.UpdateOptimistically | avg | 31ms | 35ms | 4ms | 13.06
| ClusterDiscoveryStore.SetLastPingAt | avg | 39ms | 43ms | 4ms | 10.24
| PreferenceStore.DeleteCategoryAndName | avg | 45ms | 49ms | 4ms | 8.84
| TeamStore.GetByName | avg | 49ms | 53ms | 4ms | 8.25
| StatusStore.SaveOrUpdate | avg | 90ms | 95ms | 5ms | 5.58
| PostStore.Update | avg | 93ms | 96ms | 3ms | 3.22
| PostStore.Delete | avg | 197ms | 200ms | 3ms | 1.53
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| FileInfoStore.DeleteForPost | p99 | 95ms | 447ms | 352ms | 372.49
| BotStore.Get | p99 | 233ms | 720ms | 487ms | 209.37
| PluginStore.List | p99 | 402ms | 720ms | 318ms | 79.17
| PostStore.GetPostReminders | p99 | 452ms | 720ms | 268ms | 59.34
| JobStore.Get | p99 | 243ms | 370ms | 127ms | 52.34
| JobStore.UpdateStatus | p99 | 169ms | 234ms | 65ms | 38.46
| JobStore.GetCountByStatusAndType | p99 | 352ms | 429ms | 77ms | 21.84
| TeamStore.GetByName | p99 | 484ms | 573ms | 89ms | 18.39
| ThreadStore.Get | p99 | 499ms | 584ms | 85ms | 17.02
| UserStore.IsEmpty | p99 | 312ms | 353ms | 41ms | 13.12
| ThreadStore.GetMembershipForUser | p99 | 529ms | 589ms | 60ms | 11.35
| PostStore.SetPostReminder | p99 | 520ms | 570ms | 50ms | 9.62
| GroupStore.GetByName | p99 | 410ms | 449ms | 39ms | 9.51
| ThreadStore.GetThreadFollowers | p99 | 498ms | 542ms | 44ms | 8.83
| PostPersistentNotificationStore.GetSingle | p99 | 498ms | 531ms | 33ms | 6.63
| UserStore.GetUnreadCount | p99 | 485ms | 514ms | 29ms | 5.98
| JobStore.UpdateStatusOptimistically | p99 | 221ms | 234ms | 13ms | 5.88
| SessionStore.Save | p99 | 659ms | 688ms | 29ms | 4.40
| ClusterDiscoveryStore.SetLastPingAt | p99 | 238ms | 248ms | 10ms | 4.20
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 1.315s | 1.368s | 53ms | 4.03
| StatusStore.SaveOrUpdate | p99 | 1.919s | 1.994s | 75ms | 3.91
| ThreadStore.GetTotalThreads | p99 | 511ms | 530ms | 19ms | 3.72
| PostAcknowledgementStore.GetForPosts | p99 | 715ms | 739ms | 24ms | 3.36
| UserStore.GetProfilesByUsernames | p99 | 633ms | 654ms | 21ms | 3.32
| JobStore.UpdateOptimistically | p99 | 223ms | 230ms | 7ms | 3.14
| WebhookStore.GetOutgoingByTeam | p99 | 584ms | 602ms | 18ms | 3.08
| PreferenceStore.GetAll | p99 | 470ms | 484ms | 14ms | 2.98
| PostPriorityStore.GetForPosts | p99 | 708ms | 729ms | 21ms | 2.97
| ChannelStore.GetMembersForUser | p99 | 611ms | 629ms | 18ms | 2.95
| UserStore.GetAllProfiles | p99 | 624ms | 642ms | 18ms | 2.88
| FileInfoStore.Get | p99 | 514ms | 526ms | 12ms | 2.33
| FileInfoStore.AttachToPost | p99 | 403ms | 410ms | 7ms | 1.74
| ThreadStore.GetThreadUnreadReplyCount | p99 | 623ms | 633ms | 10ms | 1.61
| ChannelStore.SaveMember | p99 | 1.594s | 1.619s | 25ms | 1.57
| ChannelStore.GetByName | p99 | 450ms | 457ms | 7ms | 1.55
| ChannelStore.GetChannelUnread | p99 | 461ms | 468ms | 7ms | 1.52
| TeamStore.GetMember | p99 | 469ms | 476ms | 7ms | 1.49
| PostStore.Update | p99 | 484ms | 491ms | 7ms | 1.45
| TeamStore.Get | p99 | 468ms | 474ms | 6ms | 1.28
| ChannelStore.GetMember | p99 | 401ms | 406ms | 5ms | 1.25
| StatusStore.UpdateExpiredDNDStatuses | p99 | 241ms | 244ms | 3ms | 1.24
| PostStore.GetPosts | p99 | 484ms | 490ms | 6ms | 1.24
| ProductNoticesStore.ClearOldNotices | p99 | 244ms | 247ms | 3ms | 1.23
| UserStore.GetForLogin | p99 | 489ms | 495ms | 6ms | 1.23
| ReactionStore.Save | p99 | 637ms | 644ms | 7ms | 1.10
| TeamStore.GetAllPage | p99 | 474ms | 479ms | 5ms | 1.05
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| UserStore.GetProfilesInChannel | avg | 245ms | 97ms | -148ms | -60.50
| PostStore.AnalyticsPostCount | avg | 2.021s | 1.09s | -931ms | -46.07
| CommandWebhookStore.Cleanup | avg | 59ms | 32ms | -27ms | -45.94
| SystemStore.Get | avg | 18ms | 11ms | -7ms | -39.00
| PostStore.GetPostReminderMetadata | avg | 66ms | 50ms | -16ms | -24.20
| PostStore.SetPostReminder | avg | 101ms | 78ms | -23ms | -22.67
| JobStore.Save | avg | 36ms | 28ms | -8ms | -22.30
| UserStore.Count | avg | 193ms | 163ms | -30ms | -15.53
| TokenStore.Cleanup | avg | 48ms | 41ms | -7ms | -14.67
| UserStore.GetByUsername | avg | 74ms | 65ms | -9ms | -12.23
| JobStore.GetNewestJobByStatusesAndType | avg | 47ms | 43ms | -4ms | -8.54
| JobStore.GetAllByStatus | avg | 66ms | 61ms | -5ms | -7.52
| UserStore.AutocompleteUsersInChannel | avg | 226ms | 209ms | -17ms | -7.51
| ChannelStore.SearchGroupChannels | avg | 96ms | 89ms | -7ms | -7.32
| ChannelStore.AutocompleteInTeamForSearch | avg | 411ms | 381ms | -30ms | -7.30
| SessionStore.GetSessionsExpired | avg | 33ms | 31ms | -2ms | -5.98
| JobStore.Get | avg | 51ms | 48ms | -3ms | -5.83
| ChannelStore.GetChannelsByUser | avg | 53ms | 50ms | -3ms | -5.68
| ThreadStore.GetTotalUnreadThreads | avg | 55ms | 52ms | -3ms | -5.50
| ThreadStore.GetTotalUnreadUrgentMentions | avg | 55ms | 52ms | -3ms | -5.48
| ChannelStore.GetMembers | avg | 110ms | 104ms | -6ms | -5.45
| PostStore.GetPostsSince | avg | 112ms | 106ms | -6ms | -5.37
| ChannelStore.Autocomplete | avg | 154ms | 146ms | -8ms | -5.19
| PostStore.GetPostsAfter | avg | 60ms | 57ms | -3ms | -5.02
| ThreadStore.GetTeamsUnreadForUser | avg | 80ms | 76ms | -4ms | -5.02
| UserStore.Search | avg | 128ms | 122ms | -6ms | -4.68
| ChannelStore.GetSidebarCategoriesForTeamForUser | avg | 176ms | 168ms | -8ms | -4.55
| PostStore.SearchPostsForUser | avg | 648ms | 619ms | -29ms | -4.47
| UserTermsOfServiceStore.GetByUser | avg | 46ms | 44ms | -2ms | -4.36
| SessionStore.GetSessionsWithActiveDeviceIds | avg | 49ms | 47ms | -2ms | -4.07
| ChannelStore.GetChannelUnread | avg | 50ms | 48ms | -2ms | -4.03
| TeamStore.GetChannelUnreadsForAllTeams | avg | 50ms | 48ms | -2ms | -4.01
| ChannelStore.GetSidebarCategory | avg | 127ms | 122ms | -5ms | -3.95
| ThreadStore.GetThreadUnreadReplyCount | avg | 76ms | 73ms | -3ms | -3.94
| ChannelStore.GetPublicChannelsForTeam | avg | 105ms | 101ms | -4ms | -3.81
| ThreadStore.GetTotalUnreadMentions | avg | 54ms | 52ms | -2ms | -3.71
| UserStore.GetUnreadCountForChannel | avg | 54ms | 52ms | -2ms | -3.70
| ChannelStore.GetTeamChannels | avg | 136ms | 131ms | -5ms | -3.67
| ThreadStore.GetTotalThreads | avg | 55ms | 53ms | -2ms | -3.65
| UserStore.Update | avg | 82ms | 79ms | -3ms | -3.65
| PostAcknowledgementStore.GetForPost | avg | 55ms | 53ms | -2ms | -3.64
| ChannelStore.GetFileCount | avg | 55ms | 53ms | -2ms | -3.64
| StatusStore.GetByIds | avg | 83ms | 80ms | -3ms | -3.61
| SessionStore.Get | avg | 58ms | 56ms | -2ms | -3.47
| ChannelStore.Save | avg | 145ms | 140ms | -5ms | -3.45
| PreferenceStore.Save | avg | 95ms | 92ms | -3ms | -3.17
| ChannelStore.UpdateSidebarCategories | avg | 478ms | 463ms | -15ms | -3.14
| UserStore.GetProfilesByUsernames | avg | 65ms | 63ms | -2ms | -3.10
| ChannelStore.GetMembersForUser | avg | 66ms | 64ms | -2ms | -3.05
| PostStore.Save | avg | 100ms | 97ms | -3ms | -3.01
| ChannelStore.GetChannels | avg | 68ms | 66ms | -2ms | -2.95
| PostStore.Get | avg | 139ms | 135ms | -4ms | -2.88
| PostStore.GetPostsByThread | avg | 70ms | 68ms | -2ms | -2.86
| ThreadStore.MaintainMembership | avg | 71ms | 69ms | -2ms | -2.81
| ThreadStore.GetThreadsForUser | avg | 74ms | 72ms | -2ms | -2.70
| ChannelStore.CreateDirectChannel | avg | 190ms | 185ms | -5ms | -2.64
| ReactionStore.Save | avg | 115ms | 112ms | -3ms | -2.62
| PostStore.GetPostsBefore | avg | 77ms | 75ms | -2ms | -2.61
| ProductNoticesStore.ClearOldNotices | avg | 79ms | 77ms | -2ms | -2.53
| ChannelStore.CreateSidebarCategory | avg | 277ms | 270ms | -7ms | -2.53
| TeamStore.SaveMember | avg | 86ms | 84ms | -2ms | -2.33
| ProductNoticesStore.View | avg | 172ms | 168ms | -4ms | -2.32
| ThreadStore.GetThreadForUser | avg | 87ms | 85ms | -2ms | -2.31
| UserStore.Save | avg | 148ms | 145ms | -3ms | -2.03
| ChannelStore.SaveMember | avg | 218ms | 214ms | -4ms | -1.83
| UserStore.InvalidateProfilesInChannelCacheByUser | avg | 471ms | 464ms | -7ms | -1.49
| UserStore.GetAllProfilesInChannel | avg | 597ms | 589ms | -8ms | -1.34
| ChannelStore.CreateInitialSidebarCategories | avg | 185ms | 183ms | -2ms | -1.08
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| CommandWebhookStore.Cleanup | p99 | 238ms | 96ms | -142ms | -59.66
| UserStore.GetProfilesInChannel | p99 | 1.948s | 819ms | -1.129s | -57.97
| SessionStore.GetSessionsExpired | p99 | 231ms | 98ms | -133ms | -57.51
| PostStore.AnalyticsPostCount | p99 | 4.9s | 2.47s | -2.43s | -49.59
| PostStore.GetPostReminderMetadata | p99 | 708ms | 472ms | -236ms | -33.32
| ReactionStore.GetForPost | p99 | 15ms | 11ms | -4ms | -25.90
| UserStore.GetByUsername | p99 | 774ms | 576ms | -198ms | -25.57
| JobStore.GetNewestJobByStatusesAndType | p99 | 478ms | 357ms | -121ms | -25.34
| UserStore.AutocompleteUsersInChannel | p99 | 1.203s | 989ms | -214ms | -17.79
| JobStore.GetAllByStatus | p99 | 651ms | 569ms | -82ms | -12.60
| PreferenceStore.DeleteCategoryAndName | p99 | 521ms | 461ms | -60ms | -11.51
| PostAcknowledgementStore.GetForPost | p99 | 663ms | 587ms | -76ms | -11.46
| PostStore.SearchPostsForUser | p99 | 6.493s | 5.801s | -692ms | -10.66
| PostPriorityStore.GetForPost | p99 | 596ms | 543ms | -53ms | -8.89
| UserStore.GetProfileByIds | p99 | 97ms | 89ms | -8ms | -8.29
| UserStore.Get | p99 | 64ms | 59ms | -5ms | -7.77
| PostStore.GetPostsByThread | p99 | 572ms | 538ms | -34ms | -5.94
| JobStore.Save | p99 | 235ms | 222ms | -13ms | -5.52
| ChannelStore.GetMembers | p99 | 1.519s | 1.439s | -80ms | -5.26
| ChannelStore.AutocompleteInTeamForSearch | p99 | 4.921s | 4.687s | -234ms | -4.75
| PostStore.GetPostsAfter | p99 | 582ms | 558ms | -24ms | -4.12
| ThreadStore.MarkAllAsReadByTeam | p99 | 249ms | 239ms | -10ms | -4.02
| ChannelStore.SearchGroupChannels | p99 | 773ms | 742ms | -31ms | -4.01
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 545ms | 525ms | -20ms | -3.67
| ChannelStore.GetChannels | p99 | 683ms | 659ms | -24ms | -3.51
| ChannelStore.GetGuestCount | p99 | 360ms | 348ms | -12ms | -3.33
| ThreadStore.GetTotalUnreadThreads | p99 | 513ms | 497ms | -16ms | -3.12
| PostStore.Delete | p99 | 998ms | 967ms | -31ms | -3.11
| UserStore.Search | p99 | 893ms | 867ms | -26ms | -2.91
| PostStore.GetPostsSince | p99 | 895ms | 869ms | -26ms | -2.91
| ChannelStore.Save | p99 | 896ms | 871ms | -25ms | -2.79
| ChannelStore.GetFileCount | p99 | 540ms | 525ms | -15ms | -2.78
| UserStore.GetMany | p99 | 197ms | 192ms | -5ms | -2.54
| ChannelStore.Autocomplete | p99 | 908ms | 886ms | -22ms | -2.42
| GroupStore.GetGroups | p99 | 581ms | 569ms | -12ms | -2.06
| ChannelStore.GetTeamChannels | p99 | 890ms | 872ms | -18ms | -2.02
| PluginStore.SetWithOptions | p99 | 403ms | 396ms | -7ms | -1.74
| FileInfoStore.Save | p99 | 248ms | 244ms | -4ms | -1.62
| StatusStore.GetByIds | p99 | 795ms | 783ms | -12ms | -1.51
| StatusStore.Get | p99 | 426ms | 420ms | -6ms | -1.41
| ThreadStore.GetTeamsUnreadForUser | p99 | 847ms | 836ms | -11ms | -1.30
| PostStore.Save | p99 | 747ms | 738ms | -9ms | -1.21
| ChannelStore.GetMemberCount | p99 | 450ms | 445ms | -5ms | -1.11
| TeamStore.GetTeamsForUser | p99 | 485ms | 480ms | -5ms | -1.03
| ThreadStore.GetTotalUnreadMentions | p99 | 500ms | 495ms | -5ms | -1.00
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| unfollowThreadByUser | avg | 236ms | 246ms | 10ms | 4.24
| deletePost | avg | 405ms | 422ms | 17ms | 4.20
| getTopThreadsForUserSince | avg | 76ms | 78ms | 2ms | 2.64
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| updateUserCustomStatus | p99 | 2.498s | 3.253s | 755ms | 30.22
| getWebappPlugins | p99 | 18ms | 22ms | 4ms | 22.25
| followThreadByUser | p99 | 1.589s | 1.75s | 161ms | 10.14
| addChannelMember | p99 | 5.702s | 6.125s | 423ms | 7.42
| unfollowThreadByUser | p99 | 1.447s | 1.534s | 87ms | 6.01
| getTopThreadsForUserSince | p99 | 758ms | 801ms | 43ms | 5.68
| getCategoriesForTeamForUser | p99 | 1.325s | 1.39s | 65ms | 4.90
| getChannelUnread | p99 | 675ms | 702ms | 27ms | 4.00
| getAllTeams | p99 | 500ms | 518ms | 18ms | 3.60
| getUsersByNames | p99 | 660ms | 677ms | 17ms | 2.58
| getChannelMembersForTeamForUser | p99 | 634ms | 650ms | 16ms | 2.52
| getChannelMembers | p99 | 869ms | 890ms | 21ms | 2.42
| getPreferences | p99 | 487ms | 498ms | 11ms | 2.26
| createGroupChannel | p99 | 8.864s | 8.987s | 123ms | 1.39
| createUser | p99 | 2.248s | 2.277s | 29ms | 1.29
| getChannelsForUser | p99 | 486ms | 492ms | 6ms | 1.23
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getTopThreadsForTeamSince | avg | 2ms | 0s | -2ms | -109.63
| patchPost | avg | 1.547s | 990ms | -557ms | -36.01
| setPostReminder | avg | 380ms | 305ms | -75ms | -19.72
| getUsers | avg | 136ms | 124ms | -12ms | -8.82
| searchPostsInTeam | avg | 1.139s | 1.054s | -85ms | -7.46
| getProfileImage | avg | 94ms | 87ms | -7ms | -7.43
| autocompleteChannelsForTeamForSearch | avg | 412ms | 382ms | -30ms | -7.28
| searchGroupChannels | avg | 97ms | 90ms | -7ms | -7.22
| autocompleteUsers | avg | 174ms | 162ms | -12ms | -6.91
| getChannelsForUser | avg | 54ms | 51ms | -3ms | -5.60
| getTeamsUnreadForUser | avg | 93ms | 88ms | -5ms | -5.38
| searchAllChannels | avg | 157ms | 149ms | -8ms | -5.10
| getPublicChannelsForTeam | avg | 109ms | 104ms | -5ms | -4.59
| getCategoriesForTeamForUser | avg | 177ms | 169ms | -8ms | -4.52
| searchUsers | avg | 134ms | 128ms | -6ms | -4.47
| createChannel | avg | 138ms | 132ms | -6ms | -4.36
| getTeamsForUser | avg | 49ms | 47ms | -2ms | -4.11
| createPost | avg | 2.19s | 2.102s | -88ms | -4.02
| followThreadByUser | avg | 234ms | 225ms | -9ms | -3.85
| getPostsForChannelAroundLastUnread | avg | 557ms | 536ms | -21ms | -3.77
| getClientConfig | avg | 82ms | 79ms | -3ms | -3.64
| login | avg | 626ms | 605ms | -21ms | -3.35
| getChannelMember | avg | 62ms | 60ms | -2ms | -3.21
| getChannelsForTeamForUser | avg | 70ms | 68ms | -2ms | -2.85
| getChannelStats | avg | 105ms | 102ms | -3ms | -2.85
| getChannel | avg | 107ms | 104ms | -3ms | -2.81
| getPostThread | avg | 400ms | 389ms | -11ms | -2.75
| updateReadStateThreadByUser | avg | 621ms | 604ms | -17ms | -2.74
| getThreadsForUser | avg | 78ms | 76ms | -2ms | -2.55
| updateCategoriesForTeamForUser | avg | 789ms | 770ms | -19ms | -2.41
| removeUserCustomStatus | avg | 770ms | 752ms | -18ms | -2.34
| updatePreferences | avg | 129ms | 126ms | -3ms | -2.33
| getFileThumbnail | avg | 173ms | 169ms | -4ms | -2.31
| createCategoryForTeamForUser | avg | 351ms | 343ms | -8ms | -2.28
| saveReaction | avg | 316ms | 309ms | -7ms | -2.21
| viewChannel | avg | 322ms | 315ms | -7ms | -2.17
| getUser | avg | 92ms | 90ms | -2ms | -2.17
| addTeamMember | avg | 3.748s | 3.671s | -77ms | -2.05
| getChannelMembers | avg | 98ms | 96ms | -2ms | -2.03
| addChannelMember | avg | 1.586s | 1.556s | -30ms | -1.89
| createUser | avg | 356ms | 350ms | -6ms | -1.68
| getFilePreview | avg | 190ms | 187ms | -3ms | -1.58
| logout | avg | 534ms | 526ms | -8ms | -1.50
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getTopThreadsForTeamSince | p99 | 75ms | 20ms | -55ms | -73.17
| getUserStatus | p99 | 14ms | 8ms | -6ms | -41.71
| updateReadStateAllThreadsByUser | p99 | 288ms | 243ms | -45ms | -15.61
| getProfileImage | p99 | 576ms | 495ms | -81ms | -14.06
| setPostReminder | p99 | 2.408s | 2.242s | -166ms | -6.89
| getTeamMembersForUser | p99 | 524ms | 499ms | -25ms | -4.78
| autocompleteChannelsForTeamForSearch | p99 | 4.921s | 4.689s | -232ms | -4.71
| getUsersByIds | p99 | 183ms | 175ms | -8ms | -4.36
| searchGroupChannels | p99 | 786ms | 753ms | -33ms | -4.20
| getUsers | p99 | 991ms | 960ms | -31ms | -3.13
| getUserStatusesByIds | p99 | 232ms | 225ms | -7ms | -3.02
| getChannelsForTeamForUser | p99 | 707ms | 687ms | -20ms | -2.83
| searchUsers | p99 | 907ms | 883ms | -24ms | -2.65
| searchAllChannels | p99 | 916ms | 896ms | -20ms | -2.18
| createCategoryForTeamForUser | p99 | 2.03s | 1.989s | -41ms | -2.02
| createChannel | p99 | 893ms | 875ms | -18ms | -2.02
| autocompleteUsers | p99 | 982ms | 966ms | -16ms | -1.63
| getPublicChannelsForTeam | p99 | 784ms | 772ms | -12ms | -1.53
| patchPost | p99 | 4.646s | 4.583s | -63ms | -1.36
| updateReadStateThreadByUser | p99 | 3.564s | 3.526s | -38ms | -1.07
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 28ms| 27ms | -1ms | -3.540
| |  P99| 228ms| 227ms | -1ms | -0.438
| BotStore.Get |  Avg| 40ms| 56ms | 16ms | 40.247
| |  P99| 233ms| 720ms | 487ms | 209.372
| BotStore.Save |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 25ms| 25ms | 0s | 0.000
| |  P99| 219ms| 219ms | 0s | 0.000
| ChannelStore.Autocomplete |  Avg| 154ms| 146ms | -8ms | -5.192
| |  P99| 908ms| 886ms | -22ms | -2.423
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 411ms| 381ms | -30ms | -7.300
| |  P99| 4.921s| 4.687s | -234ms | -4.755
| ChannelStore.CreateDirectChannel |  Avg| 190ms| 185ms | -5ms | -2.635
| |  P99| 964ms| 967ms | 3ms | 0.311
| ChannelStore.CreateInitialSidebarCategories |  Avg| 185ms| 183ms | -2ms | -1.080
| |  P99| 985ms| 989ms | 4ms | 0.406
| ChannelStore.CreateSidebarCategory |  Avg| 277ms| 270ms | -7ms | -2.526
| |  P99| 994ms| 996ms | 2ms | 0.201
| ChannelStore.Get |  Avg| 12ms| 13ms | 1ms | 8.019
| |  P99| 241ms| 243ms | 2ms | 0.829
| ChannelStore.GetAllChannelMembersForUser |  Avg| 20ms| 20ms | 0s | 0.000
| |  P99| 345ms| 344ms | -1ms | -0.290
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 55ms| 55ms | 0s | 0.000
| |  P99| 545ms| 525ms | -20ms | -3.670
| ChannelStore.GetByName |  Avg| 41ms| 40ms | -1ms | -2.451
| |  P99| 450ms| 457ms | 7ms | 1.554
| ChannelStore.GetChannelUnread |  Avg| 50ms| 48ms | -2ms | -4.030
| |  P99| 461ms| 468ms | 7ms | 1.519
| ChannelStore.GetChannels |  Avg| 68ms| 66ms | -2ms | -2.954
| |  P99| 683ms| 659ms | -24ms | -3.514
| ChannelStore.GetChannelsByUser |  Avg| 53ms| 50ms | -3ms | -5.680
| |  P99| 482ms| 486ms | 4ms | 0.830
| ChannelStore.GetFileCount |  Avg| 55ms| 53ms | -2ms | -3.635
| |  P99| 540ms| 525ms | -15ms | -2.776
| ChannelStore.GetGuestCount |  Avg| 24ms| 23ms | -1ms | -4.139
| |  P99| 360ms| 348ms | -12ms | -3.334
| ChannelStore.GetMember |  Avg| 34ms| 33ms | -1ms | -2.945
| |  P99| 401ms| 406ms | 5ms | 1.248
| ChannelStore.GetMemberCount |  Avg| 38ms| 37ms | -1ms | -2.647
| |  P99| 450ms| 445ms | -5ms | -1.112
| ChannelStore.GetMemberForPost |  Avg| 57ms| 56ms | -1ms | -1.741
| |  P99| 485ms| 484ms | -1ms | -0.206
| ChannelStore.GetMembers |  Avg| 110ms| 104ms | -6ms | -5.452
| |  P99| 1.519s| 1.439s | -80ms | -5.265
| ChannelStore.GetMembersForUser |  Avg| 66ms| 64ms | -2ms | -3.051
| |  P99| 611ms| 629ms | 18ms | 2.945
| ChannelStore.GetPinnedPostCount |  Avg| 32ms| 31ms | -1ms | -3.128
| |  P99| 415ms| 416ms | 1ms | 0.241
| ChannelStore.GetPublicChannelsForTeam |  Avg| 105ms| 101ms | -4ms | -3.805
| |  P99| 760ms| 753ms | -7ms | -0.921
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 176ms| 168ms | -8ms | -4.547
| |  P99| 1.315s| 1.368s | 53ms | 4.031
| ChannelStore.GetSidebarCategory |  Avg| 127ms| 122ms | -5ms | -3.950
| |  P99| 858ms| 853ms | -5ms | -0.583
| ChannelStore.GetTeamChannels |  Avg| 136ms| 131ms | -5ms | -3.674
| |  P99| 890ms| 872ms | -18ms | -2.022
| ChannelStore.IncrementMentionCount |  Avg| 27ms| 27ms | 0s | 0.000
| |  P99| 226ms| 226ms | 0s | 0.000
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
| ChannelStore.Save |  Avg| 145ms| 140ms | -5ms | -3.446
| |  P99| 896ms| 871ms | -25ms | -2.789
| ChannelStore.SaveMember |  Avg| 218ms| 214ms | -4ms | -1.832
| |  P99| 1.594s| 1.619s | 25ms | 1.569
| ChannelStore.SearchGroupChannels |  Avg| 96ms| 89ms | -7ms | -7.318
| |  P99| 773ms| 742ms | -31ms | -4.013
| ChannelStore.UpdateLastViewedAt |  Avg| 30ms| 29ms | -1ms | -3.363
| |  P99| 230ms| 231ms | 1ms | 0.434
| ChannelStore.UpdateSidebarCategories |  Avg| 478ms| 463ms | -15ms | -3.137
| |  P99| 2.404s| 2.389s | -15ms | -0.624
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 28ms| 27ms | -1ms | -3.598
| |  P99| 224ms| 224ms | 0s | 0.000
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 39ms| 43ms | 4ms | 10.241
| |  P99| 238ms| 248ms | 10ms | 4.195
| CommandWebhookStore.Cleanup |  Avg| 59ms| 32ms | -27ms | -45.944
| |  P99| 238ms| 96ms | -142ms | -59.664
| EmojiStore.GetMultipleByName |  Avg| 42ms| 42ms | 0s | 0.000
| |  P99| 456ms| 460ms | 4ms | 0.878
| FileInfoStore.AttachToPost |  Avg| 55ms| 54ms | -1ms | -1.815
| |  P99| 403ms| 410ms | 7ms | 1.736
| FileInfoStore.DeleteForPost |  Avg| 25ms| 48ms | 23ms | 92.090
| |  P99| 95ms| 447ms | 352ms | 372.487
| FileInfoStore.Get |  Avg| 55ms| 54ms | -1ms | -1.804
| |  P99| 514ms| 526ms | 12ms | 2.333
| FileInfoStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -16.388
| FileInfoStore.InvalidateFileInfosForPostCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.Save |  Avg| 40ms| 39ms | -1ms | -2.525
| |  P99| 248ms| 244ms | -4ms | -1.615
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 46ms| 45ms | -1ms | -2.191
| |  P99| 463ms| 466ms | 3ms | 0.648
| GroupStore.GetByName |  Avg| 35ms| 36ms | 1ms | 2.844
| |  P99| 410ms| 449ms | 39ms | 9.512
| GroupStore.GetGroups |  Avg| 56ms| 56ms | 0s | 0.000
| |  P99| 581ms| 569ms | -12ms | -2.064
| JobStore.Get |  Avg| 51ms| 48ms | -3ms | -5.833
| |  P99| 243ms| 370ms | 127ms | 52.342
| JobStore.GetAllByStatus |  Avg| 66ms| 61ms | -5ms | -7.519
| |  P99| 651ms| 569ms | -82ms | -12.600
| JobStore.GetCountByStatusAndType |  Avg| 52ms| 70ms | 18ms | 34.890
| |  P99| 352ms| 429ms | 77ms | 21.844
| JobStore.GetNewestJobByStatusesAndType |  Avg| 47ms| 43ms | -4ms | -8.543
| |  P99| 478ms| 357ms | -121ms | -25.340
| JobStore.Save |  Avg| 36ms| 28ms | -8ms | -22.298
| |  P99| 235ms| 222ms | -13ms | -5.520
| JobStore.UpdateOptimistically |  Avg| 31ms| 35ms | 4ms | 13.063
| |  P99| 223ms| 230ms | 7ms | 3.139
| JobStore.UpdateStatus |  Avg| 24ms| 35ms | 11ms | 45.749
| |  P99| 169ms| 234ms | 65ms | 38.461
| JobStore.UpdateStatusOptimistically |  Avg| 32ms| 37ms | 5ms | 15.420
| |  P99| 221ms| 234ms | 13ms | 5.882
| LinkMetadataStore.Get |  Avg| 42ms| 42ms | 0s | 0.000
| |  P99| 453ms| 457ms | 4ms | 0.883
| LinkMetadataStore.Save |  Avg| 27ms| 27ms | 0s | 0.000
| |  P99| 226ms| 225ms | -1ms | -0.443
| PluginStore.Delete |  Avg| 22ms| 21ms | -1ms | -4.544
| |  P99| 222ms| 222ms | 0s | 0.000
| PluginStore.List |  Avg| 49ms| 75ms | 26ms | 53.351
| |  P99| 402ms| 720ms | 318ms | 79.170
| PluginStore.SetWithOptions |  Avg| 46ms| 45ms | -1ms | -2.162
| |  P99| 403ms| 396ms | -7ms | -1.736
| PostAcknowledgementStore.GetForPost |  Avg| 55ms| 53ms | -2ms | -3.645
| |  P99| 663ms| 587ms | -76ms | -11.460
| PostAcknowledgementStore.GetForPosts |  Avg| 55ms| 55ms | 0s | 0.000
| |  P99| 715ms| 739ms | 24ms | 3.357
| PostPersistentNotificationStore.GetSingle |  Avg| 51ms| 51ms | 0s | 0.000
| |  P99| 498ms| 531ms | 33ms | 6.631
| PostPriorityStore.GetForPost |  Avg| 54ms| 54ms | 0s | 0.000
| |  P99| 596ms| 543ms | -53ms | -8.888
| PostPriorityStore.GetForPosts |  Avg| 56ms| 56ms | 0s | 0.000
| |  P99| 708ms| 729ms | 21ms | 2.966
| PostStore.AnalyticsPostCount |  Avg| 2.021s| 1.09s | -931ms | -46.075
| |  P99| 4.9s| 2.47s | -2.43s | -49.592
| PostStore.Delete |  Avg| 197ms| 200ms | 3ms | 1.526
| |  P99| 998ms| 967ms | -31ms | -3.106
| PostStore.Get |  Avg| 139ms| 135ms | -4ms | -2.881
| |  P99| 988ms| 984ms | -4ms | -0.405
| PostStore.GetEtag |  Avg| 27ms| 26ms | -1ms | -3.707
| |  P99| 413ms| 411ms | -2ms | -0.485
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 27ms| 26ms | -1ms | -3.667
| |  P99| 224ms| 223ms | -1ms | -0.446
| PostStore.GetPostIdBeforeTime |  Avg| 31ms| 30ms | -1ms | -3.256
| |  P99| 231ms| 230ms | -1ms | -0.433
| PostStore.GetPostReminderMetadata |  Avg| 66ms| 50ms | -16ms | -24.199
| |  P99| 708ms| 472ms | -236ms | -33.318
| PostStore.GetPostReminders |  Avg| 62ms| 81ms | 19ms | 30.703
| |  P99| 452ms| 720ms | 268ms | 59.336
| PostStore.GetPosts |  Avg| 52ms| 51ms | -1ms | -1.921
| |  P99| 484ms| 490ms | 6ms | 1.240
| PostStore.GetPostsAfter |  Avg| 60ms| 57ms | -3ms | -5.022
| |  P99| 582ms| 558ms | -24ms | -4.122
| PostStore.GetPostsBefore |  Avg| 77ms| 75ms | -2ms | -2.611
| |  P99| 743ms| 749ms | 6ms | 0.807
| PostStore.GetPostsByThread |  Avg| 70ms| 68ms | -2ms | -2.855
| |  P99| 572ms| 538ms | -34ms | -5.944
| PostStore.GetPostsSince |  Avg| 112ms| 106ms | -6ms | -5.373
| |  P99| 895ms| 869ms | -26ms | -2.906
| PostStore.GetSingle |  Avg| 55ms| 54ms | -1ms | -1.817
| |  P99| 498ms| 497ms | -1ms | -0.201
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 100ms| 97ms | -3ms | -3.008
| |  P99| 747ms| 738ms | -9ms | -1.205
| PostStore.SearchPostsForUser |  Avg| 648ms| 619ms | -29ms | -4.474
| |  P99| 6.493s| 5.801s | -692ms | -10.658
| PostStore.SetPostReminder |  Avg| 101ms| 78ms | -23ms | -22.671
| |  P99| 520ms| 570ms | 50ms | 9.616
| PostStore.Update |  Avg| 93ms| 96ms | 3ms | 3.223
| |  P99| 484ms| 491ms | 7ms | 1.447
| PreferenceStore.DeleteCategoryAndName |  Avg| 45ms| 49ms | 4ms | 8.845
| |  P99| 521ms| 461ms | -60ms | -11.509
| PreferenceStore.Get |  Avg| 52ms| 51ms | -1ms | -1.935
| |  P99| 492ms| 491ms | -1ms | -0.203
| PreferenceStore.GetAll |  Avg| 49ms| 50ms | 1ms | 2.023
| |  P99| 470ms| 484ms | 14ms | 2.977
| PreferenceStore.Save |  Avg| 95ms| 92ms | -3ms | -3.171
| |  P99| 495ms| 494ms | -1ms | -0.202
| ProductNoticesStore.ClearOldNotices |  Avg| 79ms| 77ms | -2ms | -2.531
| |  P99| 244ms| 247ms | 3ms | 1.230
| ProductNoticesStore.View |  Avg| 172ms| 168ms | -4ms | -2.323
| |  P99| 972ms| 979ms | 7ms | 0.721
| ReactionStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 15ms| 11ms | -4ms | -25.896
| ReactionStore.Save |  Avg| 115ms| 112ms | -3ms | -2.619
| |  P99| 637ms| 644ms | 7ms | 1.099
| RoleStore.ChannelHigherScopedPermissions |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| RoleStore.GetByNames |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Get |  Avg| 58ms| 56ms | -2ms | -3.471
| |  P99| 445ms| 447ms | 2ms | 0.449
| SessionStore.GetSessionsExpired |  Avg| 33ms| 31ms | -2ms | -5.977
| |  P99| 231ms| 98ms | -133ms | -57.514
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 49ms| 47ms | -2ms | -4.073
| |  P99| 484ms| 487ms | 3ms | 0.620
| SessionStore.Remove |  Avg| 30ms| 30ms | 0s | 0.000
| |  P99| 226ms| 225ms | -1ms | -0.443
| SessionStore.Save |  Avg| 70ms| 70ms | 0s | 0.000
| |  P99| 659ms| 688ms | 29ms | 4.401
| SessionStore.UpdateLastActivityAt |  Avg| 30ms| 30ms | 0s | 0.000
| |  P99| 229ms| 229ms | 0s | 0.000
| StatusStore.Get |  Avg| 34ms| 34ms | 0s | 0.000
| |  P99| 426ms| 420ms | -6ms | -1.408
| StatusStore.GetByIds |  Avg| 83ms| 80ms | -3ms | -3.610
| |  P99| 795ms| 783ms | -12ms | -1.510
| StatusStore.SaveOrUpdate |  Avg| 90ms| 95ms | 5ms | 5.584
| |  P99| 1.919s| 1.994s | 75ms | 3.907
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 49ms| 50ms | 1ms | 2.029
| |  P99| 241ms| 244ms | 3ms | 1.243
| StatusStore.UpdateLastActivityAt |  Avg| 29ms| 29ms | 0s | 0.000
| |  P99| 226ms| 226ms | 0s | 0.000
| SystemStore.Get |  Avg| 18ms| 11ms | -7ms | -39.000
| |  P99| 25ms| 25ms | 0s | 0.000
| SystemStore.GetByName |  Avg| 27ms| 26ms | -1ms | -3.689
| |  P99| 231ms| 229ms | -2ms | -0.867
| TeamStore.AnalyticsTeamCount |  Avg| 33ms| 33ms | 0s | 0.000
| |  P99| 436ms| 439ms | 3ms | 0.688
| TeamStore.Get |  Avg| 45ms| 45ms | 0s | 0.000
| |  P99| 468ms| 474ms | 6ms | 1.281
| TeamStore.GetAllPage |  Avg| 47ms| 46ms | -1ms | -2.150
| |  P99| 474ms| 479ms | 5ms | 1.054
| TeamStore.GetByName |  Avg| 49ms| 53ms | 4ms | 8.246
| |  P99| 484ms| 573ms | 89ms | 18.388
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 50ms| 48ms | -2ms | -4.006
| |  P99| 479ms| 483ms | 4ms | 0.836
| TeamStore.GetMember |  Avg| 49ms| 48ms | -1ms | -2.062
| |  P99| 469ms| 476ms | 7ms | 1.491
| TeamStore.GetTeamsByUserId |  Avg| 47ms| 46ms | -1ms | -2.112
| |  P99| 472ms| 470ms | -2ms | -0.424
| TeamStore.GetTeamsForUser |  Avg| 48ms| 47ms | -1ms | -2.080
| |  P99| 485ms| 480ms | -5ms | -1.031
| TeamStore.InvalidateAllTeamIdsForUser |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.SaveMember |  Avg| 86ms| 84ms | -2ms | -2.333
| |  P99| 471ms| 474ms | 3ms | 0.637
| ThreadStore.Get |  Avg| 55ms| 55ms | 0s | 0.000
| |  P99| 499ms| 584ms | 85ms | 17.022
| ThreadStore.GetMembershipForUser |  Avg| 52ms| 53ms | 1ms | 1.906
| |  P99| 529ms| 589ms | 60ms | 11.352
| ThreadStore.GetTeamsUnreadForUser |  Avg| 80ms| 76ms | -4ms | -5.020
| |  P99| 847ms| 836ms | -11ms | -1.299
| ThreadStore.GetThreadFollowers |  Avg| 50ms| 50ms | 0s | 0.000
| |  P99| 498ms| 542ms | 44ms | 8.831
| ThreadStore.GetThreadForUser |  Avg| 87ms| 85ms | -2ms | -2.310
| |  P99| 838ms| 845ms | 7ms | 0.835
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 76ms| 73ms | -3ms | -3.939
| |  P99| 623ms| 633ms | 10ms | 1.606
| ThreadStore.GetThreadsForUser |  Avg| 74ms| 72ms | -2ms | -2.703
| |  P99| 692ms| 688ms | -4ms | -0.578
| ThreadStore.GetTotalThreads |  Avg| 55ms| 53ms | -2ms | -3.653
| |  P99| 511ms| 530ms | 19ms | 3.720
| ThreadStore.GetTotalUnreadMentions |  Avg| 54ms| 52ms | -2ms | -3.707
| |  P99| 500ms| 495ms | -5ms | -1.001
| ThreadStore.GetTotalUnreadThreads |  Avg| 55ms| 52ms | -3ms | -5.503
| |  P99| 513ms| 497ms | -16ms | -3.121
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 55ms| 52ms | -3ms | -5.480
| |  P99| 498ms| 496ms | -2ms | -0.402
| ThreadStore.MaintainMembership |  Avg| 71ms| 69ms | -2ms | -2.809
| |  P99| 464ms| 463ms | -1ms | -0.216
| ThreadStore.MarkAllAsReadByChannels |  Avg| 29ms| 28ms | -1ms | -3.495
| |  P99| 228ms| 228ms | 0s | 0.000
| ThreadStore.MarkAllAsReadByTeam |  Avg| 42ms| 41ms | -1ms | -2.376
| |  P99| 249ms| 239ms | -10ms | -4.021
| ThreadStore.MarkAsRead |  Avg| 29ms| 29ms | 0s | 0.000
| |  P99| 228ms| 228ms | 0s | 0.000
| ThreadStore.UpdateMembership |  Avg| 29ms| 29ms | 0s | 0.000
| |  P99| 225ms| 225ms | 0s | 0.000
| TokenStore.Cleanup |  Avg| 48ms| 41ms | -7ms | -14.669
| |  P99| 99ms| 99ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 59ms| 59ms | 0s | 0.000
| |  P99| 616ms| 618ms | 2ms | 0.325
| UserStore.AutocompleteUsersInChannel |  Avg| 226ms| 209ms | -17ms | -7.514
| |  P99| 1.203s| 989ms | -214ms | -17.794
| UserStore.Count |  Avg| 193ms| 163ms | -30ms | -15.532
| |  P99| 922ms| 922ms | 0s | 0.000
| UserStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 64ms| 59ms | -5ms | -7.769
| UserStore.GetAllProfiles |  Avg| 52ms| 52ms | 0s | 0.000
| |  P99| 624ms| 642ms | 18ms | 2.885
| UserStore.GetAllProfilesInChannel |  Avg| 597ms| 589ms | -8ms | -1.341
| |  P99| 4.49s| 4.478s | -12ms | -0.267
| UserStore.GetByUsername |  Avg| 74ms| 65ms | -9ms | -12.234
| |  P99| 774ms| 576ms | -198ms | -25.565
| UserStore.GetForLogin |  Avg| 47ms| 46ms | -1ms | -2.141
| |  P99| 489ms| 495ms | 6ms | 1.227
| UserStore.GetMany |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 197ms| 192ms | -5ms | -2.543
| UserStore.GetProfileByIds |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 97ms| 89ms | -8ms | -8.286
| UserStore.GetProfilesByUsernames |  Avg| 65ms| 63ms | -2ms | -3.100
| |  P99| 633ms| 654ms | 21ms | 3.315
| UserStore.GetProfilesInChannel |  Avg| 245ms| 97ms | -148ms | -60.500
| |  P99| 1.948s| 819ms | -1.129s | -57.970
| UserStore.GetUnreadCount |  Avg| 50ms| 49ms | -1ms | -2.002
| |  P99| 485ms| 514ms | 29ms | 5.979
| UserStore.GetUnreadCountForChannel |  Avg| 54ms| 52ms | -2ms | -3.702
| |  P99| 489ms| 487ms | -2ms | -0.409
| UserStore.InvalidateProfileCacheForUser |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.InvalidateProfilesInChannelCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.InvalidateProfilesInChannelCacheByUser |  Avg| 471ms| 464ms | -7ms | -1.486
| |  P99| 2.354s| 2.353s | -1ms | -0.042
| UserStore.IsEmpty |  Avg| 22ms| 22ms | 0s | 0.000
| |  P99| 312ms| 353ms | 41ms | 13.120
| UserStore.Save |  Avg| 148ms| 145ms | -3ms | -2.027
| |  P99| 711ms| 714ms | 3ms | 0.422
| UserStore.Search |  Avg| 128ms| 122ms | -6ms | -4.676
| |  P99| 893ms| 867ms | -26ms | -2.913
| UserStore.Update |  Avg| 82ms| 79ms | -3ms | -3.650
| |  P99| 465ms| 463ms | -2ms | -0.430
| UserStore.UpdateFailedPasswordAttempts |  Avg| 29ms| 28ms | -1ms | -3.483
| |  P99| 229ms| 228ms | -1ms | -0.437
| UserStore.UpdateUpdateAt |  Avg| 22ms| 22ms | 0s | 0.000
| |  P99| 210ms| 210ms | 0s | 0.000
| UserTermsOfServiceStore.GetByUser |  Avg| 46ms| 44ms | -2ms | -4.357
| |  P99| 474ms| 475ms | 1ms | 0.211
| WebhookStore.GetOutgoingByTeam |  Avg| 59ms| 58ms | -1ms | -1.704
| |  P99| 584ms| 602ms | 18ms | 3.084
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 1.586s| 1.556s | -30ms | -1.892
| | P99| 5.702s| 6.125s | 423ms | 7.418
| addTeamMember | Avg| 3.748s| 3.671s | -77ms | -2.055
| | P99| 10s| 10s | 0s | 0.000
| autocompleteChannelsForTeamForSearch | Avg| 412ms| 382ms | -30ms | -7.282
| | P99| 4.921s| 4.689s | -232ms | -4.714
| autocompleteUsers | Avg| 174ms| 162ms | -12ms | -6.905
| | P99| 982ms| 966ms | -16ms | -1.630
| createCategoryForTeamForUser | Avg| 351ms| 343ms | -8ms | -2.278
| | P99| 2.03s| 1.989s | -41ms | -2.020
| createChannel | Avg| 138ms| 132ms | -6ms | -4.358
| | P99| 893ms| 875ms | -18ms | -2.015
| createDirectChannel | Avg| 1.284s| 1.273s | -11ms | -0.857
| | P99| 4.748s| 4.768s | 20ms | 0.421
| createGroupChannel | Avg| 2.229s| 2.223s | -6ms | -0.269
| | P99| 8.864s| 8.987s | 123ms | 1.388
| createPost | Avg| 2.19s| 2.102s | -88ms | -4.019
| | P99| 9.474s| 9.49s | 16ms | 0.169
| createUser | Avg| 356ms| 350ms | -6ms | -1.684
| | P99| 2.248s| 2.277s | 29ms | 1.290
| deletePost | Avg| 405ms| 422ms | 17ms | 4.199
| | P99| 2.379s| 2.378s | -1ms | -0.042
| followThreadByUser | Avg| 234ms| 225ms | -9ms | -3.845
| | P99| 1.589s| 1.75s | 161ms | 10.135
| getAllTeams | Avg| 53ms| 52ms | -1ms | -1.891
| | P99| 500ms| 518ms | 18ms | 3.602
| getCategoriesForTeamForUser | Avg| 177ms| 169ms | -8ms | -4.516
| | P99| 1.325s| 1.39s | 65ms | 4.905
| getChannel | Avg| 107ms| 104ms | -3ms | -2.805
| | P99| 913ms| 911ms | -2ms | -0.219
| getChannelMember | Avg| 62ms| 60ms | -2ms | -3.212
| | P99| 493ms| 491ms | -2ms | -0.406
| getChannelMembers | Avg| 98ms| 96ms | -2ms | -2.033
| | P99| 869ms| 890ms | 21ms | 2.416
| getChannelMembersForTeamForUser | Avg| 67ms| 66ms | -1ms | -1.487
| | P99| 634ms| 650ms | 16ms | 2.525
| getChannelStats | Avg| 105ms| 102ms | -3ms | -2.849
| | P99| 982ms| 978ms | -4ms | -0.407
| getChannelUnread | Avg| 66ms| 65ms | -1ms | -1.507
| | P99| 675ms| 702ms | 27ms | 4.003
| getChannelsForTeamForUser | Avg| 70ms| 68ms | -2ms | -2.853
| | P99| 707ms| 687ms | -20ms | -2.829
| getChannelsForUser | Avg| 54ms| 51ms | -3ms | -5.599
| | P99| 486ms| 492ms | 6ms | 1.234
| getClientConfig | Avg| 82ms| 79ms | -3ms | -3.640
| | P99| 499ms| 498ms | -1ms | -0.200
| getFilePreview | Avg| 190ms| 187ms | -3ms | -1.575
| | P99| 991ms| 993ms | 2ms | 0.202
| getFileThumbnail | Avg| 173ms| 169ms | -4ms | -2.315
| | P99| 982ms| 981ms | -1ms | -0.102
| getPostThread | Avg| 400ms| 389ms | -11ms | -2.751
| | P99| 2.49s| 2.48s | -10ms | -0.402
| getPostsForChannel | Avg| 1.748s| 1.732s | -16ms | -0.916
| | P99| 10s| 10s | 0s | 0.000
| getPostsForChannelAroundLastUnread | Avg| 557ms| 536ms | -21ms | -3.772
| | P99| 4.863s| 4.83s | -33ms | -0.679
| getPreferences | Avg| 53ms| 53ms | 0s | 0.000
| | P99| 487ms| 498ms | 11ms | 2.259
| getProfileImage | Avg| 94ms| 87ms | -7ms | -7.430
| | P99| 576ms| 495ms | -81ms | -14.057
| getPublicChannelsForTeam | Avg| 109ms| 104ms | -5ms | -4.586
| | P99| 784ms| 772ms | -12ms | -1.531
| getTeamMembersForUser | Avg| 53ms| 52ms | -1ms | -1.872
| | P99| 524ms| 499ms | -25ms | -4.775
| getTeamsForUser | Avg| 49ms| 47ms | -2ms | -4.112
| | P99| 480ms| 478ms | -2ms | -0.416
| getTeamsUnreadForUser | Avg| 93ms| 88ms | -5ms | -5.379
| | P99| 934ms| 926ms | -8ms | -0.857
| getThreadsForUser | Avg| 78ms| 76ms | -2ms | -2.554
| | P99| 757ms| 752ms | -5ms | -0.660
| getTopThreadsForTeamSince | Avg| 2ms| 0s | -2ms | -109.630
| | P99| 75ms| 20ms | -55ms | -73.171
| getTopThreadsForUserSince | Avg| 76ms| 78ms | 2ms | 2.644
| | P99| 758ms| 801ms | 43ms | 5.677
| getUser | Avg| 92ms| 90ms | -2ms | -2.170
| | P99| 871ms| 867ms | -4ms | -0.459
| getUserStatus | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 14ms| 8ms | -6ms | -41.708
| getUserStatusesByIds | Avg| 9ms| 8ms | -1ms | -10.864
| | P99| 232ms| 225ms | -7ms | -3.016
| getUsers | Avg| 136ms| 124ms | -12ms | -8.824
| | P99| 991ms| 960ms | -31ms | -3.127
| getUsersByIds | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 183ms| 175ms | -8ms | -4.362
| getUsersByNames | Avg| 66ms| 65ms | -1ms | -1.507
| | P99| 660ms| 677ms | 17ms | 2.576
| getWebappPlugins | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 18ms| 22ms | 4ms | 22.249
| login | Avg| 626ms| 605ms | -21ms | -3.353
| | P99| 3.757s| 3.731s | -26ms | -0.692
| logout | Avg| 534ms| 526ms | -8ms | -1.497
| | P99| 2.37s| 2.37s | 0s | 0.000
| patchPost | Avg| 1.547s| 990ms | -557ms | -36.014
| | P99| 4.646s| 4.583s | -63ms | -1.356
| removeUserCustomStatus | Avg| 770ms| 752ms | -18ms | -2.337
| | P99| 2.462s| 2.453s | -9ms | -0.366
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 316ms| 309ms | -7ms | -2.214
| | P99| 2.172s| 2.179s | 7ms | 0.322
| searchAllChannels | Avg| 157ms| 149ms | -8ms | -5.099
| | P99| 916ms| 896ms | -20ms | -2.184
| searchGroupChannels | Avg| 97ms| 90ms | -7ms | -7.219
| | P99| 786ms| 753ms | -33ms | -4.196
| searchPostsInTeam | Avg| 1.139s| 1.054s | -85ms | -7.464
| | P99| 10s| 10s | 0s | 0.000
| searchUsers | Avg| 134ms| 128ms | -6ms | -4.470
| | P99| 907ms| 883ms | -24ms | -2.646
| setPostReminder | Avg| 380ms| 305ms | -75ms | -19.719
| | P99| 2.408s| 2.242s | -166ms | -6.894
| unfollowThreadByUser | Avg| 236ms| 246ms | 10ms | 4.242
| | P99| 1.447s| 1.534s | 87ms | 6.012
| updateCategoriesForTeamForUser | Avg| 789ms| 770ms | -19ms | -2.407
| | P99| 3.743s| 3.773s | 30ms | 0.801
| updatePreferences | Avg| 129ms| 126ms | -3ms | -2.329
| | P99| 775ms| 776ms | 1ms | 0.129
| updateReadStateAllThreadsByUser | Avg| 44ms| 43ms | -1ms | -2.263
| | P99| 288ms| 243ms | -45ms | -15.610
| updateReadStateThreadByUser | Avg| 621ms| 604ms | -17ms | -2.740
| | P99| 3.564s| 3.526s | -38ms | -1.066
| updateUserCustomStatus | Avg| 909ms| 908ms | -1ms | -0.110
| | P99| 2.498s| 3.253s | 755ms | 30.221
| uploadFileStream | Avg| 780ms| 776ms | -4ms | -0.513
| | P99| 2.452s| 2.452s | 0s | 0.000
| viewChannel | Avg| 322ms| 315ms | -7ms | -2.174
| | P99| 2.313s| 2.315s | 2ms | 0.086
