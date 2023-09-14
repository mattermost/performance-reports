### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostPersistentNotificationStore.DeleteExpired | avg | 2ms | 12ms | 10ms | 452.36
| LinkMetadataStore.Save | avg | 4ms | 20ms | 16ms | 400.02
| ThreadStore.MarkAllAsReadByTeam | avg | 8ms | 38ms | 30ms | 358.14
| StatusStore.UpdateExpiredDNDStatuses | avg | 12ms | 49ms | 37ms | 314.60
| PostPersistentNotificationStore.Get | avg | 3ms | 12ms | 9ms | 303.86
| BotStore.Get | avg | 46ms | 159ms | 113ms | 247.51
| UserAccessTokenStore.GetByToken | avg | 47ms | 122ms | 75ms | 159.99
| PreferenceStore.DeleteCategoryAndName | avg | 16ms | 41ms | 25ms | 152.95
| UserStore.GetProfilesInChannel | avg | 108ms | 267ms | 159ms | 147.18
| JobStore.UpdateStatusOptimistically | avg | 8ms | 19ms | 11ms | 135.35
| PostStore.GetPostIdAfterTime | avg | 5ms | 12ms | 7ms | 132.33
| UserStore.Count | avg | 139ms | 323ms | 184ms | 132.25
| ThreadStore.MarkAllAsReadByChannels | avg | 10ms | 23ms | 13ms | 128.73
| ChannelStore.UpdateSidebarChannelsByPreferences | avg | 7ms | 16ms | 9ms | 120.10
| ClusterDiscoveryStore.SetLastPingAt | avg | 10ms | 22ms | 12ms | 120.01
| JobStore.UpdateOptimistically | avg | 6ms | 13ms | 7ms | 115.10
| ReactionStore.Save | avg | 30ms | 63ms | 33ms | 109.42
| ThreadStore.MaintainMembership | avg | 18ms | 38ms | 20ms | 108.73
| SessionStore.GetSessionsExpired | avg | 26ms | 54ms | 28ms | 108.12
| PostStore.GetPostIdBeforeTime | avg | 8ms | 17ms | 9ms | 107.22
| JobStore.UpdateStatus | avg | 7ms | 14ms | 7ms | 106.12
| SystemStore.GetByName | avg | 5ms | 10ms | 5ms | 102.85
| JobStore.GetNewestJobByStatusesAndType | avg | 45ms | 91ms | 46ms | 102.17
| ChannelStore.UpdateLastViewedAt | avg | 17ms | 34ms | 17ms | 101.02
| StatusStore.UpdateLastActivityAt | avg | 11ms | 22ms | 11ms | 99.58
| ChannelStore.GetTeamChannels | avg | 112ms | 219ms | 107ms | 95.76
| ChannelStore.IncrementMentionCount | avg | 8ms | 16ms | 8ms | 94.69
| PluginStore.Delete | avg | 4ms | 8ms | 4ms | 94.24
| PostStore.GetPostReminders | avg | 15ms | 29ms | 14ms | 93.76
| SessionStore.UpdateLastActivityAt | avg | 10ms | 19ms | 9ms | 90.25
| PluginStore.SetWithOptions | avg | 10ms | 19ms | 9ms | 86.91
| JobStore.Get | avg | 67ms | 125ms | 58ms | 86.67
| PostStore.Update | avg | 38ms | 70ms | 32ms | 84.48
| ThreadStore.UpdateMembership | avg | 11ms | 20ms | 9ms | 82.68
| PostStore.Save | avg | 32ms | 58ms | 26ms | 82.12
| PostStore.Delete | avg | 82ms | 148ms | 66ms | 80.46
| ThreadStore.MarkAsRead | avg | 10ms | 18ms | 8ms | 79.99
| ProductNoticesStore.View | avg | 63ms | 111ms | 48ms | 75.75
| SessionStore.Get | avg | 13ms | 22ms | 9ms | 69.97
| FileInfoStore.Save | avg | 13ms | 22ms | 9ms | 66.70
| UserStore.UpdateFailedPasswordAttempts | avg | 9ms | 15ms | 6ms | 64.06
| PreferenceStore.Save | avg | 20ms | 33ms | 13ms | 63.84
| JobStore.GetCountByStatusAndType | avg | 52ms | 85ms | 33ms | 62.88
| FileInfoStore.AttachToPost | avg | 18ms | 29ms | 11ms | 62.39
| ChannelMemberHistoryStore.LogJoinEvent | avg | 7ms | 11ms | 4ms | 59.13
| UserStore.Update | avg | 25ms | 40ms | 15ms | 58.90
| FileInfoStore.Get | avg | 37ms | 59ms | 22ms | 58.77
| AuditStore.Save | avg | 9ms | 14ms | 5ms | 57.76
| UserStore.UpdateUpdateAt | avg | 7ms | 11ms | 4ms | 57.64
| ChannelStore.GetMemberForPost | avg | 35ms | 55ms | 20ms | 57.08
| ChannelStore.GetGuestCount | avg | 50ms | 77ms | 27ms | 54.18
| ChannelStore.CreateDirectChannel | avg | 205ms | 312ms | 107ms | 52.27
| JobStore.Save | avg | 8ms | 12ms | 4ms | 52.02
| ChannelStore.GetPinnedPostCount | avg | 47ms | 71ms | 24ms | 50.63
| StatusStore.SaveOrUpdate | avg | 67ms | 101ms | 34ms | 50.50
| ChannelStore.Save | avg | 92ms | 136ms | 44ms | 47.81
| ChannelStore.GetFileCount | avg | 36ms | 53ms | 17ms | 46.98
| TeamStore.GetMember | avg | 4ms | 6ms | 2ms | 45.99
| ChannelStore.CreateInitialSidebarCategories | avg | 62ms | 88ms | 26ms | 42.18
| PostPriorityStore.GetForPost | avg | 55ms | 76ms | 21ms | 38.13
| GroupStore.GetByName | avg | 29ms | 40ms | 11ms | 38.13
| UserStore.GetProfilesByUsernames | avg | 48ms | 66ms | 18ms | 37.87
| UserStore.GetProfileByIds | avg | 43ms | 59ms | 16ms | 37.13
| FileInfoStore.GetForPost | avg | 49ms | 67ms | 18ms | 36.41
| SessionStore.Save | avg | 44ms | 60ms | 16ms | 36.10
| ChannelStore.UpdateSidebarCategories | avg | 263ms | 356ms | 93ms | 35.29
| PostPriorityStore.GetForPosts | avg | 94ms | 126ms | 32ms | 33.87
| LinkMetadataStore.Get | avg | 57ms | 76ms | 19ms | 33.48
| ChannelStore.SaveMember | avg | 168ms | 221ms | 53ms | 31.57
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 48ms | 63ms | 15ms | 31.42
| UserStore.GetForLogin | avg | 36ms | 47ms | 11ms | 30.88
| PostAcknowledgementStore.GetForPost | avg | 53ms | 69ms | 16ms | 30.10
| ChannelStore.GetMembers | avg | 296ms | 384ms | 88ms | 29.69
| ReactionStore.GetForPost | avg | 72ms | 92ms | 20ms | 27.85
| PostStore.GetSingle | avg | 57ms | 73ms | 16ms | 27.84
| PostAcknowledgementStore.GetForPosts | avg | 95ms | 121ms | 26ms | 27.47
| UserTermsOfServiceStore.GetByUser | avg | 44ms | 56ms | 12ms | 26.99
| ChannelStore.GetSidebarCategory | avg | 103ms | 130ms | 27ms | 26.30
| ChannelStore.SearchGroupChannels | avg | 80ms | 101ms | 21ms | 26.26
| StatusStore.Get | avg | 28ms | 35ms | 7ms | 25.43
| TeamStore.Get | avg | 56ms | 70ms | 14ms | 24.91
| UserStore.IsEmpty | avg | 21ms | 26ms | 5ms | 24.25
| PostStore.GetEtag | avg | 68ms | 84ms | 16ms | 23.53
| TeamStore.GetTeamsForUser | avg | 43ms | 53ms | 10ms | 23.09
| PostStore.GetPosts | avg | 39ms | 48ms | 9ms | 22.96
| ChannelStore.Get | avg | 88ms | 108ms | 20ms | 22.72
| JobStore.GetAllByStatus | avg | 67ms | 82ms | 15ms | 22.55
| SessionStore.GetSessionsWithActiveDeviceIds | avg | 50ms | 61ms | 11ms | 21.89
| UserStore.Get | avg | 28ms | 34ms | 6ms | 21.81
| TeamStore.GetAllPage | avg | 46ms | 56ms | 10ms | 21.69
| ThreadStore.GetTotalUnreadThreads | avg | 48ms | 58ms | 10ms | 21.00
| PostStore.GetPostsBefore | avg | 67ms | 81ms | 14ms | 20.93
| UserStore.GetMany | avg | 54ms | 65ms | 11ms | 20.39
| ChannelStore.GetByName | avg | 36ms | 43ms | 7ms | 19.68
| UserStore.Save | avg | 87ms | 104ms | 17ms | 19.48
| StatusStore.GetByIds | avg | 87ms | 104ms | 17ms | 19.45
| PostPersistentNotificationStore.GetSingle | avg | 67ms | 80ms | 13ms | 19.31
| PreferenceStore.Get | avg | 64ms | 76ms | 12ms | 18.71
| GroupStore.AdminRoleGroupsForSyncableMember | avg | 37ms | 44ms | 7ms | 18.67
| ThreadStore.GetTotalUnreadUrgentMentions | avg | 50ms | 59ms | 9ms | 18.12
| TeamStore.GetTeamsByUserId | avg | 50ms | 59ms | 9ms | 18.11
| PostStore.Get | avg | 131ms | 154ms | 23ms | 17.61
| TeamStore.SaveMember | avg | 116ms | 136ms | 20ms | 17.28
| ChannelStore.GetMemberCount | avg | 316ms | 368ms | 52ms | 16.47
| ThreadStore.GetTotalThreads | avg | 50ms | 58ms | 8ms | 16.11
| TeamStore.GetChannelUnreadsForAllTeams | avg | 50ms | 58ms | 8ms | 15.93
| ChannelStore.GetAllChannelMembersForUser | avg | 13ms | 15ms | 2ms | 15.80
| ThreadStore.GetTotalUnreadMentions | avg | 51ms | 59ms | 8ms | 15.78
| PostStore.GetPostReminderMetadata | avg | 83ms | 96ms | 13ms | 15.71
| WebhookStore.GetOutgoingByTeam | avg | 74ms | 85ms | 11ms | 14.87
| PreferenceStore.GetAll | avg | 55ms | 63ms | 8ms | 14.68
| GroupStore.GetGroups | avg | 62ms | 71ms | 9ms | 14.52
| CommandWebhookStore.Cleanup | avg | 21ms | 24ms | 3ms | 14.46
| ThreadStore.GetThreadsForUser | avg | 83ms | 94ms | 11ms | 13.31
| ChannelStore.GetChannels | avg | 77ms | 87ms | 10ms | 12.94
| ChannelStore.GetMembersForUser | avg | 71ms | 80ms | 9ms | 12.66
| ChannelStore.Autocomplete | avg | 319ms | 359ms | 40ms | 12.55
| UserStore.GetAllProfiles | avg | 49ms | 55ms | 6ms | 12.30
| ChannelStore.GetSidebarCategoriesForTeamForUser | avg | 116ms | 130ms | 14ms | 12.03
| ThreadStore.GetMembershipForUser | avg | 66ms | 73ms | 7ms | 10.59
| ThreadStore.GetThreadFollowers | avg | 71ms | 78ms | 7ms | 9.92
| ThreadStore.GetThreadForUser | avg | 101ms | 110ms | 9ms | 8.95
| ChannelStore.GetChannelsByUser | avg | 80ms | 86ms | 6ms | 7.50
| ThreadStore.GetThreadUnreadReplyCount | avg | 84ms | 90ms | 6ms | 7.15
| UserStore.GetUnreadCount | avg | 62ms | 66ms | 4ms | 6.46
| ThreadStore.GetTeamsUnreadForUser | avg | 85ms | 89ms | 4ms | 4.70
| UserStore.Search | avg | 205ms | 214ms | 9ms | 4.39
| PostStore.GetPostsByThread | avg | 77ms | 80ms | 3ms | 3.91
| PluginStore.List | avg | 83ms | 86ms | 3ms | 3.61
| PostStore.GetPostsSince | avg | 127ms | 130ms | 3ms | 2.36
| UserStore.AutocompleteUsersInChannel | avg | 602ms | 613ms | 11ms | 1.83
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| BotStore.Get | p99 | 430ms | 4.225s | 3.795s | 882.56
| ChannelStore.GetTeamChannels | p99 | 248ms | 2.245s | 1.997s | 806.48
| LinkMetadataStore.Save | p99 | 23ms | 97ms | 74ms | 321.05
| ThreadStore.MarkAllAsReadByTeam | p99 | 25ms | 99ms | 74ms | 301.43
| PostPersistentNotificationStore.Get | p99 | 22ms | 87ms | 65ms | 300.59
| UserStore.GetProfilesInChannel | p99 | 248ms | 980ms | 732ms | 295.46
| JobStore.UpdateStatus | p99 | 44ms | 125ms | 81ms | 184.44
| StatusStore.UpdateExpiredDNDStatuses | p99 | 86ms | 243ms | 157ms | 182.56
| JobStore.UpdateStatusOptimistically | p99 | 82ms | 207ms | 125ms | 152.91
| SessionStore.GetSessionsExpired | p99 | 97ms | 244ms | 147ms | 151.09
| PostPersistentNotificationStore.DeleteExpired | p99 | 39ms | 94ms | 55ms | 141.94
| ClusterDiscoveryStore.SetLastPingAt | p99 | 90ms | 207ms | 117ms | 130.16
| PostStore.SearchPostsForUser | p99 | 990ms | 2.265s | 1.275s | 128.72
| StatusStore.UpdateLastActivityAt | p99 | 92ms | 206ms | 114ms | 123.58
| UserAccessTokenStore.GetByToken | p99 | 428ms | 932ms | 504ms | 117.89
| PluginStore.List | p99 | 720ms | 1.54s | 820ms | 113.88
| PluginStore.SetWithOptions | p99 | 104ms | 219ms | 115ms | 111.10
| UserStore.Count | p99 | 463ms | 970ms | 507ms | 109.62
| ThreadStore.MarkAllAsReadByChannels | p99 | 96ms | 198ms | 102ms | 106.04
| FileInfoStore.Save | p99 | 101ms | 205ms | 104ms | 102.73
| CommandWebhookStore.Cleanup | p99 | 49ms | 98ms | 49ms | 100.00
| PostStore.GetPostIdBeforeTime | p99 | 92ms | 183ms | 91ms | 99.29
| ChannelStore.IncrementMentionCount | p99 | 91ms | 180ms | 89ms | 98.13
| SessionStore.Remove | p99 | 96ms | 189ms | 93ms | 96.62
| SessionStore.UpdateLastActivityAt | p99 | 87ms | 171ms | 84ms | 96.36
| ChannelStore.GetMembers | p99 | 1.073s | 2.105s | 1.032s | 96.21
| JobStore.Save | p99 | 63ms | 123ms | 60ms | 96.00
| ThreadStore.UpdateMembership | p99 | 92ms | 179ms | 87ms | 94.87
| PreferenceStore.DeleteCategoryAndName | p99 | 228ms | 440ms | 212ms | 93.18
| UserStore.UpdateFailedPasswordAttempts | p99 | 89ms | 172ms | 83ms | 92.89
| StatusStore.SaveOrUpdate | p99 | 915ms | 1.757s | 842ms | 91.98
| PostStore.Delete | p99 | 462ms | 880ms | 418ms | 90.38
| PostStore.Save | p99 | 255ms | 473ms | 218ms | 85.49
| AuditStore.Save | p99 | 88ms | 163ms | 75ms | 84.91
| PluginStore.Delete | p99 | 50ms | 92ms | 42ms | 84.76
| ReactionStore.Save | p99 | 242ms | 433ms | 191ms | 78.96
| ProductNoticesStore.View | p99 | 527ms | 942ms | 415ms | 78.72
| PostStore.GetPostIdAfterTime | p99 | 76ms | 135ms | 59ms | 78.00
| PostStore.Update | p99 | 237ms | 419ms | 182ms | 76.92
| UserStore.GetMany | p99 | 237ms | 417ms | 180ms | 75.95
| ChannelStore.GetMemberCount | p99 | 998ms | 1.746s | 748ms | 74.95
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 249ms | 425ms | 176ms | 70.56
| PostAcknowledgementStore.GetForPost | p99 | 520ms | 836ms | 316ms | 60.77
| JobStore.Get | p99 | 817ms | 1.255s | 438ms | 53.58
| ChannelStore.GetPinnedPostCount | p99 | 510ms | 748ms | 238ms | 46.66
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 69ms | 101ms | 32ms | 46.39
| UserStore.UpdateUpdateAt | p99 | 67ms | 98ms | 31ms | 46.33
| ChannelStore.GetGuestCount | p99 | 569ms | 826ms | 257ms | 45.20
| ThreadStore.MarkAsRead | p99 | 84ms | 120ms | 36ms | 42.82
| TeamStore.SaveMember | p99 | 494ms | 702ms | 208ms | 42.09
| UserStore.Save | p99 | 333ms | 463ms | 130ms | 38.99
| UserStore.GetProfilesByUsernames | p99 | 495ms | 661ms | 166ms | 33.52
| ChannelStore.UpdateLastViewedAt | p99 | 181ms | 239ms | 58ms | 32.06
| FileInfoStore.Get | p99 | 440ms | 575ms | 135ms | 30.69
| SystemStore.GetByName | p99 | 78ms | 100ms | 22ms | 28.04
| TeamStore.GetMember | p99 | 74ms | 94ms | 20ms | 27.15
| JobStore.GetCountByStatusAndType | p99 | 620ms | 785ms | 165ms | 26.61
| ChannelStore.CreateInitialSidebarCategories | p99 | 636ms | 801ms | 165ms | 25.95
| ChannelStore.GetAllChannelMembersForUser | p99 | 244ms | 307ms | 63ms | 25.81
| JobStore.UpdateOptimistically | p99 | 63ms | 79ms | 16ms | 25.20
| SessionStore.Get | p99 | 186ms | 231ms | 45ms | 24.21
| ChannelStore.GetMemberForPost | p99 | 425ms | 518ms | 93ms | 21.88
| JobStore.GetNewestJobByStatusesAndType | p99 | 747ms | 910ms | 163ms | 21.83
| ThreadStore.MaintainMembership | p99 | 206ms | 249ms | 43ms | 20.85
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 539ms | 651ms | 112ms | 20.76
| UserStore.GetProfileByIds | p99 | 540ms | 652ms | 112ms | 20.76
| StatusStore.Get | p99 | 361ms | 431ms | 70ms | 19.38
| FileInfoStore.AttachToPost | p99 | 198ms | 232ms | 34ms | 17.16
| SessionStore.Save | p99 | 473ms | 554ms | 81ms | 17.13
| PostPriorityStore.GetForPosts | p99 | 1.424s | 1.664s | 240ms | 16.85
| ChannelStore.UpdateSidebarChannelsByPreferences | p99 | 85ms | 99ms | 14ms | 16.44
| ChannelStore.SaveMember | p99 | 1.884s | 2.171s | 287ms | 15.24
| GroupStore.GetByName | p99 | 389ms | 447ms | 58ms | 14.91
| PostAcknowledgementStore.GetForPosts | p99 | 1.407s | 1.599s | 192ms | 13.65
| UserStore.GetForLogin | p99 | 443ms | 495ms | 52ms | 11.75
| UserStore.IsEmpty | p99 | 331ms | 368ms | 37ms | 11.16
| UserTermsOfServiceStore.GetByUser | p99 | 494ms | 549ms | 55ms | 11.13
| ChannelStore.GetFileCount | p99 | 428ms | 472ms | 44ms | 10.28
| PreferenceStore.Save | p99 | 226ms | 249ms | 23ms | 10.19
| ChannelStore.GetByName | p99 | 429ms | 472ms | 43ms | 10.02
| PostPriorityStore.GetForPost | p99 | 687ms | 754ms | 67ms | 9.76
| PostStore.GetPostReminders | p99 | 208ms | 227ms | 19ms | 9.13
| UserStore.Update | p99 | 227ms | 246ms | 19ms | 8.38
| TeamStore.GetTeamsForUser | p99 | 485ms | 522ms | 37ms | 7.62
| UserStore.Search | p99 | 1.384s | 1.481s | 97ms | 7.01
| UserStore.Get | p99 | 428ms | 457ms | 29ms | 6.78
| ChannelStore.SearchGroupChannels | p99 | 882ms | 941ms | 59ms | 6.69
| TeamStore.GetAllPage | p99 | 526ms | 554ms | 28ms | 5.32
| LinkMetadataStore.Get | p99 | 786ms | 815ms | 29ms | 3.69
| PostStore.GetPostsBefore | p99 | 791ms | 816ms | 25ms | 3.16
| PostStore.GetPosts | p99 | 453ms | 467ms | 14ms | 3.09
| UserStore.GetAllProfilesInChannel | p99 | 4.598s | 4.738s | 140ms | 3.04
| PostStore.GetEtag | p99 | 826ms | 849ms | 23ms | 2.78
| FileInfoStore.GetForPost | p99 | 736ms | 752ms | 16ms | 2.18
| PostPersistentNotificationStore.GetSingle | p99 | 837ms | 851ms | 14ms | 1.67
| PostStore.GetSingle | p99 | 790ms | 801ms | 11ms | 1.39
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| EmojiStore.GetMultipleByName | avg | 58ms | 0s | -58ms | -100.85
| UserStore.GetUnreadCountForChannel | avg | 49ms | 0s | -49ms | -99.96
| ProductNoticesStore.ClearOldNotices | avg | 18ms | 1ms | -17ms | -96.90
| ChannelStore.CreateSidebarCategory | avg | 149ms | 70ms | -79ms | -52.99
| RoleStore.ChannelHigherScopedPermissions | avg | 72ms | 44ms | -28ms | -38.77
| PostStore.AnalyticsPostCount | avg | 10.956s | 6.908s | -4.048s | -36.95
| ThreadStore.Get | avg | 118ms | 94ms | -24ms | -20.31
| UserStore.GetByUsername | avg | 96ms | 80ms | -16ms | -16.69
| PostStore.GetPostsAfter | avg | 89ms | 82ms | -7ms | -7.87
| ChannelStore.GetPublicChannelsForTeam | avg | 107ms | 100ms | -7ms | -6.54
| ChannelStore.GetChannelUnread | avg | 86ms | 84ms | -2ms | -2.32
| ChannelStore.AutocompleteInTeamForSearch | avg | 488ms | 480ms | -8ms | -1.64
| PostStore.SearchPostsForUser | avg | 207ms | 204ms | -3ms | -1.45
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| EmojiStore.GetMultipleByName | p99 | 801ms | 0s | -801ms | -100.01
| UserStore.GetUnreadCountForChannel | p99 | 635ms | 0s | -635ms | -99.98
| ProductNoticesStore.ClearOldNotices | p99 | 50ms | 5ms | -45ms | -90.87
| PostStore.SetPostReminder | p99 | 825ms | 241ms | -584ms | -70.79
| ThreadStore.Get | p99 | 2.1s | 943ms | -1.157s | -55.09
| ChannelStore.CreateSidebarCategory | p99 | 493ms | 245ms | -248ms | -50.36
| ChannelStore.Save | p99 | 1.36s | 813ms | -547ms | -40.22
| RoleStore.ChannelHigherScopedPermissions | p99 | 761ms | 456ms | -305ms | -40.06
| ChannelStore.AutocompleteInTeamForSearch | p99 | 3.508s | 2.467s | -1.041s | -29.67
| TeamStore.GetByName | p99 | 808ms | 577ms | -231ms | -28.59
| ChannelStore.GetPublicChannelsForTeam | p99 | 1.125s | 804ms | -321ms | -28.54
| ThreadStore.GetThreadForUser | p99 | 1.263s | 1s | -263ms | -20.82
| PostStore.GetPostsAfter | p99 | 934ms | 748ms | -186ms | -19.92
| ChannelStore.Autocomplete | p99 | 6.06s | 5.148s | -912ms | -15.05
| UserStore.GetByUsername | p99 | 882ms | 750ms | -132ms | -14.97
| ChannelStore.GetChannelUnread | p99 | 904ms | 771ms | -133ms | -14.71
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 632ms | 549ms | -83ms | -13.14
| TeamStore.GetTeamsByUserId | p99 | 638ms | 559ms | -79ms | -12.39
| JobStore.GetAllByStatus | p99 | 912ms | 816ms | -96ms | -10.52
| PostStore.GetPostsByThread | p99 | 931ms | 836ms | -95ms | -10.20
| ThreadStore.GetThreadUnreadReplyCount | p99 | 981ms | 883ms | -98ms | -9.99
| ChannelStore.GetChannelsByUser | p99 | 823ms | 749ms | -74ms | -8.99
| PreferenceStore.GetAll | p99 | 676ms | 618ms | -58ms | -8.58
| UserStore.GetAllProfiles | p99 | 670ms | 615ms | -55ms | -8.21
| ChannelStore.GetMember | p99 | 378ms | 349ms | -29ms | -7.66
| UserStore.GetUnreadCount | p99 | 870ms | 808ms | -62ms | -7.13
| ThreadStore.GetThreadFollowers | p99 | 904ms | 852ms | -52ms | -5.75
| ThreadStore.GetTotalThreads | p99 | 602ms | 570ms | -32ms | -5.32
| PostStore.GetPostReminderMetadata | p99 | 1.48s | 1.405s | -75ms | -5.07
| StatusStore.GetByIds | p99 | 1.024s | 973ms | -51ms | -4.98
| ThreadStore.GetTeamsUnreadForUser | p99 | 997ms | 952ms | -45ms | -4.51
| ChannelStore.GetSidebarCategory | p99 | 1s | 957ms | -43ms | -4.30
| PostStore.Get | p99 | 1.713s | 1.64s | -73ms | -4.26
| ChannelStore.GetMembersForUser | p99 | 863ms | 827ms | -36ms | -4.17
| ThreadStore.GetMembershipForUser | p99 | 821ms | 787ms | -34ms | -4.14
| ThreadStore.GetThreadsForUser | p99 | 929ms | 892ms | -37ms | -3.98
| PostStore.GetPostsSince | p99 | 961ms | 927ms | -34ms | -3.54
| GroupStore.GetGroups | p99 | 800ms | 772ms | -28ms | -3.50
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 474ms | 460ms | -14ms | -2.96
| WebhookStore.GetOutgoingByTeam | p99 | 856ms | 831ms | -25ms | -2.92
| ThreadStore.GetTotalUnreadThreads | p99 | 579ms | 567ms | -12ms | -2.07
| ChannelStore.GetChannels | p99 | 881ms | 865ms | -16ms | -1.82
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| updateReadStateAllThreadsByUser | avg | 8ms | 38ms | 30ms | 353.28
| getChannelMembers | avg | 58ms | 215ms | 157ms | 271.56
| updatePreferences | avg | 37ms | 74ms | 37ms | 98.98
| createChannel | avg | 112ms | 219ms | 107ms | 95.62
| followThreadByUser | avg | 147ms | 283ms | 136ms | 92.23
| getClientConfig | avg | 15ms | 28ms | 13ms | 87.07
| getTeamMember | avg | 15ms | 24ms | 9ms | 60.34
| logout | avg | 207ms | 319ms | 112ms | 54.15
| createDirectChannel | avg | 717ms | 1.1s | 383ms | 53.44
| getChannel | avg | 100ms | 152ms | 52ms | 51.98
| getFileThumbnail | avg | 109ms | 165ms | 56ms | 51.32
| createGroupChannel | avg | 1.334s | 1.987s | 653ms | 48.93
| getFilePreview | avg | 114ms | 168ms | 54ms | 47.40
| login | avg | 223ms | 312ms | 89ms | 39.91
| getUsersByNames | avg | 48ms | 67ms | 19ms | 39.31
| getChannelMember | avg | 57ms | 77ms | 20ms | 34.80
| updateCategoriesForTeamForUser | avg | 531ms | 704ms | 173ms | 32.60
| getUser | avg | 58ms | 76ms | 18ms | 30.81
| saveReaction | avg | 253ms | 327ms | 74ms | 29.29
| getChannelStats | avg | 83ms | 107ms | 24ms | 28.96
| getUsersByIds | avg | 7ms | 9ms | 2ms | 28.84
| createUser | avg | 184ms | 233ms | 49ms | 26.68
| searchGroupChannels | avg | 80ms | 101ms | 21ms | 26.19
| getTeamMembersForUser | avg | 45ms | 56ms | 11ms | 24.55
| patchPost | avg | 2.82s | 3.51s | 690ms | 24.47
| getAllTeams | avg | 47ms | 58ms | 11ms | 23.21
| getUsers | avg | 60ms | 72ms | 12ms | 20.12
| getTeamsForUser | avg | 50ms | 59ms | 9ms | 18.07
| removeUserCustomStatus | avg | 400ms | 468ms | 68ms | 17.02
| getPreferences | avg | 55ms | 64ms | 9ms | 16.39
| createPost | avg | 3.61s | 4.164s | 554ms | 15.35
| getChannelsForTeamForUser | avg | 76ms | 86ms | 10ms | 13.09
| searchAllChannels | avg | 321ms | 362ms | 41ms | 12.76
| getChannelMembersForTeamForUser | avg | 71ms | 80ms | 9ms | 12.68
| addChannelMember | avg | 1.476s | 1.661s | 185ms | 12.53
| updateReadStateThreadByUser | avg | 601ms | 675ms | 74ms | 12.31
| getCategoriesForTeamForUser | avg | 117ms | 131ms | 14ms | 12.01
| uploadFileStream | avg | 529ms | 591ms | 62ms | 11.73
| updateUserCustomStatus | avg | 608ms | 679ms | 71ms | 11.68
| addTeamMember | avg | 2.694s | 2.985s | 291ms | 10.80
| getThreadsForUser | avg | 89ms | 98ms | 9ms | 10.07
| getTeamsUnreadForUser | avg | 95ms | 103ms | 8ms | 8.40
| getChannelsForUser | avg | 80ms | 86ms | 6ms | 7.48
| deletePost | avg | 384ms | 405ms | 21ms | 5.47
| searchUsers | avg | 209ms | 218ms | 9ms | 4.32
| autocompleteUsers | avg | 492ms | 501ms | 9ms | 1.83
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| createChannel | p99 | 248ms | 2.245s | 1.997s | 806.48
| updateReadStateAllThreadsByUser | p99 | 25ms | 99ms | 74ms | 301.43
| getUserStatusesByIds | p99 | 24ms | 67ms | 43ms | 177.55
| followThreadByUser | p99 | 850ms | 1.945s | 1.095s | 128.82
| createGroupChannel | p99 | 4.819s | 8.961s | 4.142s | 85.95
| getChannel | p99 | 984ms | 1.69s | 706ms | 71.71
| getChannelStats | p99 | 985ms | 1.634s | 649ms | 65.87
| updatePreferences | p99 | 278ms | 451ms | 173ms | 62.24
| createUser | p99 | 961ms | 1.468s | 507ms | 52.77
| getUsersByIds | p99 | 140ms | 209ms | 69ms | 49.36
| getTeamMember | p99 | 164ms | 236ms | 72ms | 43.85
| getUsersByNames | p99 | 498ms | 680ms | 182ms | 36.51
| getClientConfig | p99 | 219ms | 291ms | 72ms | 32.84
| getFileThumbnail | p99 | 874ms | 1.108s | 234ms | 26.78
| getChannelMember | p99 | 606ms | 745ms | 139ms | 22.93
| getFilePreview | p99 | 860ms | 994ms | 134ms | 15.59
| login | p99 | 2.099s | 2.393s | 294ms | 14.01
| uploadFileStream | p99 | 2.096s | 2.37s | 274ms | 13.07
| getTeamMembersForUser | p99 | 488ms | 548ms | 60ms | 12.30
| removeUserCustomStatus | p99 | 2.113s | 2.332s | 219ms | 10.37
| searchUsers | p99 | 1.404s | 1.53s | 126ms | 8.97
| patchPost | p99 | 9.248s | 10s | 752ms | 8.13
| createDirectChannel | p99 | 4.178s | 4.494s | 316ms | 7.56
| searchGroupChannels | p99 | 882ms | 942ms | 60ms | 6.81
| getAllTeams | p99 | 539ms | 573ms | 34ms | 6.31
| logout | p99 | 925ms | 966ms | 41ms | 4.43
| getUser | p99 | 727ms | 758ms | 31ms | 4.26
| updateCategoriesForTeamForUser | p99 | 2.393s | 2.452s | 59ms | 2.47
| getChannelMembers | p99 | 244ms | 249ms | 5ms | 2.05
| saveReaction | p99 | 2.336s | 2.369s | 33ms | 1.41
| getProfileImage | p99 | 472ms | 478ms | 6ms | 1.27
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getPostsForChannel | avg | 3.361s | 1.075s | -2.286s | -68.02
| createCategoryForTeamForUser | avg | 203ms | 128ms | -75ms | -37.01
| setPostReminder | avg | 450ms | 291ms | -159ms | -35.37
| searchPostsInTeam | avg | 529ms | 421ms | -108ms | -20.42
| unfollowThreadByUser | avg | 270ms | 220ms | -50ms | -18.52
| viewChannel | avg | 241ms | 206ms | -35ms | -14.52
| getPostsForChannelAroundLastUnread | avg | 300ms | 267ms | -33ms | -11.01
| getPublicChannelsForTeam | avg | 109ms | 102ms | -7ms | -6.43
| getProfileImage | avg | 88ms | 84ms | -4ms | -4.55
| getChannelUnread | avg | 93ms | 91ms | -2ms | -2.15
| autocompleteChannelsForTeamForSearch | avg | 489ms | 480ms | -9ms | -1.84
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| unfollowThreadByUser | p99 | 3.151s | 970ms | -2.181s | -69.22
| updateUserCustomStatus | p99 | 5.826s | 2.428s | -3.398s | -58.32
| createCategoryForTeamForUser | p99 | 985ms | 483ms | -502ms | -50.96
| searchPostsInTeam | p99 | 8.38s | 4.843s | -3.537s | -42.21
| getPostsForChannelAroundLastUnread | p99 | 3.724s | 2.395s | -1.329s | -35.68
| autocompleteChannelsForTeamForSearch | p99 | 3.508s | 2.467s | -1.041s | -29.67
| getPublicChannelsForTeam | p99 | 1.125s | 804ms | -321ms | -28.54
| viewChannel | p99 | 2.33s | 1.889s | -441ms | -18.93
| setPostReminder | p99 | 2.369s | 1.93s | -439ms | -18.53
| getTeamsUnreadForUser | p99 | 1.221s | 1.006s | -215ms | -17.61
| getPostThread | p99 | 4.501s | 3.784s | -717ms | -15.93
| searchAllChannels | p99 | 6.06s | 5.148s | -912ms | -15.05
| getChannelUnread | p99 | 912ms | 798ms | -114ms | -12.50
| getTeamsForUser | p99 | 638ms | 563ms | -75ms | -11.76
| getChannelsForUser | p99 | 826ms | 749ms | -77ms | -9.32
| getPreferences | p99 | 679ms | 623ms | -56ms | -8.25
| updateReadStateThreadByUser | p99 | 4.706s | 4.412s | -294ms | -6.25
| addChannelMember | p99 | 9.275s | 8.725s | -550ms | -5.93
| getThreadsForUser | p99 | 994ms | 943ms | -51ms | -5.13
| getChannelMembersForTeamForUser | p99 | 860ms | 828ms | -32ms | -3.72
| getUsers | p99 | 805ms | 788ms | -17ms | -2.11
| getChannelsForTeamForUser | p99 | 874ms | 862ms | -12ms | -1.37
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 9ms| 14ms | 5ms | 57.756
| |  P99| 88ms| 163ms | 75ms | 84.914
| BotStore.Get |  Avg| 46ms| 159ms | 113ms | 247.509
| |  P99| 430ms| 4.225s | 3.795s | 882.558
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 7ms| 11ms | 4ms | 59.133
| |  P99| 69ms| 101ms | 32ms | 46.392
| ChannelStore.Autocomplete |  Avg| 319ms| 359ms | 40ms | 12.555
| |  P99| 6.06s| 5.148s | -912ms | -15.049
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 488ms| 480ms | -8ms | -1.638
| |  P99| 3.508s| 2.467s | -1.041s | -29.674
| ChannelStore.CreateDirectChannel |  Avg| 205ms| 312ms | 107ms | 52.268
| |  P99| 2.23s| 2.241s | 11ms | 0.493
| ChannelStore.CreateInitialSidebarCategories |  Avg| 62ms| 88ms | 26ms | 42.178
| |  P99| 636ms| 801ms | 165ms | 25.949
| ChannelStore.CreateSidebarCategory |  Avg| 149ms| 70ms | -79ms | -52.989
| |  P99| 493ms| 245ms | -248ms | -50.355
| ChannelStore.Get |  Avg| 88ms| 108ms | 20ms | 22.716
| |  P99| 964ms| 955ms | -9ms | -0.934
| ChannelStore.GetAllChannelMembersForUser |  Avg| 13ms| 15ms | 2ms | 15.798
| |  P99| 244ms| 307ms | 63ms | 25.811
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 48ms| 63ms | 15ms | 31.422
| |  P99| 249ms| 425ms | 176ms | 70.557
| ChannelStore.GetByName |  Avg| 36ms| 43ms | 7ms | 19.679
| |  P99| 429ms| 472ms | 43ms | 10.022
| ChannelStore.GetChannelUnread |  Avg| 86ms| 84ms | -2ms | -2.316
| |  P99| 904ms| 771ms | -133ms | -14.711
| ChannelStore.GetChannels |  Avg| 77ms| 87ms | 10ms | 12.937
| |  P99| 881ms| 865ms | -16ms | -1.816
| ChannelStore.GetChannelsByUser |  Avg| 80ms| 86ms | 6ms | 7.504
| |  P99| 823ms| 749ms | -74ms | -8.989
| ChannelStore.GetFileCount |  Avg| 36ms| 53ms | 17ms | 46.984
| |  P99| 428ms| 472ms | 44ms | 10.279
| ChannelStore.GetGuestCount |  Avg| 50ms| 77ms | 27ms | 54.175
| |  P99| 569ms| 826ms | 257ms | 45.204
| ChannelStore.GetMember |  Avg| 26ms| 26ms | 0s | 0.000
| |  P99| 378ms| 349ms | -29ms | -7.664
| ChannelStore.GetMemberCount |  Avg| 316ms| 368ms | 52ms | 16.471
| |  P99| 998ms| 1.746s | 748ms | 74.953
| ChannelStore.GetMemberForPost |  Avg| 35ms| 55ms | 20ms | 57.082
| |  P99| 425ms| 518ms | 93ms | 21.883
| ChannelStore.GetMembers |  Avg| 296ms| 384ms | 88ms | 29.685
| |  P99| 1.073s| 2.105s | 1.032s | 96.213
| ChannelStore.GetMembersForUser |  Avg| 71ms| 80ms | 9ms | 12.663
| |  P99| 863ms| 827ms | -36ms | -4.172
| ChannelStore.GetPinnedPostCount |  Avg| 47ms| 71ms | 24ms | 50.631
| |  P99| 510ms| 748ms | 238ms | 46.658
| ChannelStore.GetPublicChannelsForTeam |  Avg| 107ms| 100ms | -7ms | -6.537
| |  P99| 1.125s| 804ms | -321ms | -28.541
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 116ms| 130ms | 14ms | 12.033
| |  P99| 1.226s| 1.23s | 4ms | 0.326
| ChannelStore.GetSidebarCategory |  Avg| 103ms| 130ms | 27ms | 26.302
| |  P99| 1s| 957ms | -43ms | -4.299
| ChannelStore.GetTeamChannels |  Avg| 112ms| 219ms | 107ms | 95.765
| |  P99| 248ms| 2.245s | 1.997s | 806.479
| ChannelStore.IncrementMentionCount |  Avg| 8ms| 16ms | 8ms | 94.693
| |  P99| 91ms| 180ms | 89ms | 98.133
| ChannelStore.InvalidateAllChannelMembersForUser |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.InvalidateChannelByName |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.Save |  Avg| 92ms| 136ms | 44ms | 47.807
| |  P99| 1.36s| 813ms | -547ms | -40.220
| ChannelStore.SaveMember |  Avg| 168ms| 221ms | 53ms | 31.569
| |  P99| 1.884s| 2.171s | 287ms | 15.235
| ChannelStore.SearchGroupChannels |  Avg| 80ms| 101ms | 21ms | 26.256
| |  P99| 882ms| 941ms | 59ms | 6.692
| ChannelStore.UpdateLastViewedAt |  Avg| 17ms| 34ms | 17ms | 101.025
| |  P99| 181ms| 239ms | 58ms | 32.062
| ChannelStore.UpdateSidebarCategories |  Avg| 263ms| 356ms | 93ms | 35.295
| |  P99| 2.25s| 2.249s | -1ms | -0.044
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 7ms| 16ms | 9ms | 120.102
| |  P99| 85ms| 99ms | 14ms | 16.438
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 10ms| 22ms | 12ms | 120.014
| |  P99| 90ms| 207ms | 117ms | 130.163
| CommandWebhookStore.Cleanup |  Avg| 21ms| 24ms | 3ms | 14.456
| |  P99| 49ms| 98ms | 49ms | 99.999
| EmojiStore.GetMultipleByName |  Avg| 58ms| 0s | -58ms | -100.847
| |  P99| 801ms| 0s | -801ms | -100.005
| FileInfoStore.AttachToPost |  Avg| 18ms| 29ms | 11ms | 62.387
| |  P99| 198ms| 232ms | 34ms | 17.157
| FileInfoStore.Get |  Avg| 37ms| 59ms | 22ms | 58.770
| |  P99| 440ms| 575ms | 135ms | 30.694
| FileInfoStore.GetForPost |  Avg| 49ms| 67ms | 18ms | 36.405
| |  P99| 736ms| 752ms | 16ms | 2.175
| FileInfoStore.Save |  Avg| 13ms| 22ms | 9ms | 66.701
| |  P99| 101ms| 205ms | 104ms | 102.729
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 37ms| 44ms | 7ms | 18.673
| |  P99| 474ms| 460ms | -14ms | -2.956
| GroupStore.GetByName |  Avg| 29ms| 40ms | 11ms | 38.127
| |  P99| 389ms| 447ms | 58ms | 14.906
| GroupStore.GetGroups |  Avg| 62ms| 71ms | 9ms | 14.517
| |  P99| 800ms| 772ms | -28ms | -3.501
| JobStore.Get |  Avg| 67ms| 125ms | 58ms | 86.667
| |  P99| 817ms| 1.255s | 438ms | 53.578
| JobStore.GetAllByStatus |  Avg| 67ms| 82ms | 15ms | 22.547
| |  P99| 912ms| 816ms | -96ms | -10.522
| JobStore.GetCountByStatusAndType |  Avg| 52ms| 85ms | 33ms | 62.877
| |  P99| 620ms| 785ms | 165ms | 26.613
| JobStore.GetNewestJobByStatusesAndType |  Avg| 45ms| 91ms | 46ms | 102.172
| |  P99| 747ms| 910ms | 163ms | 21.830
| JobStore.Save |  Avg| 8ms| 12ms | 4ms | 52.017
| |  P99| 63ms| 123ms | 60ms | 96.000
| JobStore.UpdateOptimistically |  Avg| 6ms| 13ms | 7ms | 115.105
| |  P99| 63ms| 79ms | 16ms | 25.199
| JobStore.UpdateStatus |  Avg| 7ms| 14ms | 7ms | 106.121
| |  P99| 44ms| 125ms | 81ms | 184.440
| JobStore.UpdateStatusOptimistically |  Avg| 8ms| 19ms | 11ms | 135.353
| |  P99| 82ms| 207ms | 125ms | 152.906
| LinkMetadataStore.Get |  Avg| 57ms| 76ms | 19ms | 33.476
| |  P99| 786ms| 815ms | 29ms | 3.689
| LinkMetadataStore.Save |  Avg| 4ms| 20ms | 16ms | 400.020
| |  P99| 23ms| 97ms | 74ms | 321.045
| PluginStore.Delete |  Avg| 4ms| 8ms | 4ms | 94.235
| |  P99| 50ms| 92ms | 42ms | 84.760
| PluginStore.List |  Avg| 83ms| 86ms | 3ms | 3.615
| |  P99| 720ms| 1.54s | 820ms | 113.876
| PluginStore.SetWithOptions |  Avg| 10ms| 19ms | 9ms | 86.910
| |  P99| 104ms| 219ms | 115ms | 111.103
| PostAcknowledgementStore.GetForPost |  Avg| 53ms| 69ms | 16ms | 30.103
| |  P99| 520ms| 836ms | 316ms | 60.770
| PostAcknowledgementStore.GetForPosts |  Avg| 95ms| 121ms | 26ms | 27.472
| |  P99| 1.407s| 1.599s | 192ms | 13.649
| PostPersistentNotificationStore.DeleteExpired |  Avg| 2ms| 12ms | 10ms | 452.358
| |  P99| 39ms| 94ms | 55ms | 141.943
| PostPersistentNotificationStore.Get |  Avg| 3ms| 12ms | 9ms | 303.855
| |  P99| 22ms| 87ms | 65ms | 300.586
| PostPersistentNotificationStore.GetSingle |  Avg| 67ms| 80ms | 13ms | 19.310
| |  P99| 837ms| 851ms | 14ms | 1.673
| PostPriorityStore.GetForPost |  Avg| 55ms| 76ms | 21ms | 38.133
| |  P99| 687ms| 754ms | 67ms | 9.757
| PostPriorityStore.GetForPosts |  Avg| 94ms| 126ms | 32ms | 33.874
| |  P99| 1.424s| 1.664s | 240ms | 16.853
| PostStore.AnalyticsPostCount |  Avg| 10.956s| 6.908s | -4.048s | -36.949
| |  P99| 10s| 9.95s | -50ms | -0.500
| PostStore.Delete |  Avg| 82ms| 148ms | 66ms | 80.460
| |  P99| 462ms| 880ms | 418ms | 90.382
| PostStore.Get |  Avg| 131ms| 154ms | 23ms | 17.610
| |  P99| 1.713s| 1.64s | -73ms | -4.261
| PostStore.GetEtag |  Avg| 68ms| 84ms | 16ms | 23.530
| |  P99| 826ms| 849ms | 23ms | 2.783
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 5ms| 12ms | 7ms | 132.333
| |  P99| 76ms| 135ms | 59ms | 77.995
| PostStore.GetPostIdBeforeTime |  Avg| 8ms| 17ms | 9ms | 107.222
| |  P99| 92ms| 183ms | 91ms | 99.292
| PostStore.GetPostReminderMetadata |  Avg| 83ms| 96ms | 13ms | 15.713
| |  P99| 1.48s| 1.405s | -75ms | -5.068
| PostStore.GetPostReminders |  Avg| 15ms| 29ms | 14ms | 93.762
| |  P99| 208ms| 227ms | 19ms | 9.135
| PostStore.GetPosts |  Avg| 39ms| 48ms | 9ms | 22.957
| |  P99| 453ms| 467ms | 14ms | 3.090
| PostStore.GetPostsAfter |  Avg| 89ms| 82ms | -7ms | -7.872
| |  P99| 934ms| 748ms | -186ms | -19.917
| PostStore.GetPostsBefore |  Avg| 67ms| 81ms | 14ms | 20.934
| |  P99| 791ms| 816ms | 25ms | 3.161
| PostStore.GetPostsByThread |  Avg| 77ms| 80ms | 3ms | 3.906
| |  P99| 931ms| 836ms | -95ms | -10.201
| PostStore.GetPostsSince |  Avg| 127ms| 130ms | 3ms | 2.364
| |  P99| 961ms| 927ms | -34ms | -3.538
| PostStore.GetSingle |  Avg| 57ms| 73ms | 16ms | 27.845
| |  P99| 790ms| 801ms | 11ms | 1.393
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 32ms| 58ms | 26ms | 82.122
| |  P99| 255ms| 473ms | 218ms | 85.492
| PostStore.SearchPostsForUser |  Avg| 207ms| 204ms | -3ms | -1.449
| |  P99| 990ms| 2.265s | 1.275s | 128.725
| PostStore.SetPostReminder |  Avg| 46ms| 47ms | 1ms | 2.152
| |  P99| 825ms| 241ms | -584ms | -70.792
| PostStore.Update |  Avg| 38ms| 70ms | 32ms | 84.478
| |  P99| 237ms| 419ms | 182ms | 76.919
| PreferenceStore.DeleteCategoryAndName |  Avg| 16ms| 41ms | 25ms | 152.952
| |  P99| 228ms| 440ms | 212ms | 93.182
| PreferenceStore.Get |  Avg| 64ms| 76ms | 12ms | 18.712
| |  P99| 811ms| 803ms | -8ms | -0.987
| PreferenceStore.GetAll |  Avg| 55ms| 63ms | 8ms | 14.675
| |  P99| 676ms| 618ms | -58ms | -8.576
| PreferenceStore.Save |  Avg| 20ms| 33ms | 13ms | 63.837
| |  P99| 226ms| 249ms | 23ms | 10.192
| ProductNoticesStore.ClearOldNotices |  Avg| 18ms| 1ms | -17ms | -96.897
| |  P99| 50ms| 5ms | -45ms | -90.867
| ProductNoticesStore.View |  Avg| 63ms| 111ms | 48ms | 75.752
| |  P99| 527ms| 942ms | 415ms | 78.715
| ReactionStore.GetForPost |  Avg| 72ms| 92ms | 20ms | 27.848
| |  P99| 887ms| 882ms | -5ms | -0.563
| ReactionStore.Save |  Avg| 30ms| 63ms | 33ms | 109.417
| |  P99| 242ms| 433ms | 191ms | 78.957
| RoleStore.ChannelHigherScopedPermissions |  Avg| 72ms| 44ms | -28ms | -38.768
| |  P99| 761ms| 456ms | -305ms | -40.063
| RoleStore.GetByNames |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Get |  Avg| 13ms| 22ms | 9ms | 69.975
| |  P99| 186ms| 231ms | 45ms | 24.214
| SessionStore.GetSessionsExpired |  Avg| 26ms| 54ms | 28ms | 108.122
| |  P99| 97ms| 244ms | 147ms | 151.085
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 50ms| 61ms | 11ms | 21.885
| |  P99| 539ms| 651ms | 112ms | 20.762
| SessionStore.Remove |  Avg| 16ms| 17ms | 1ms | 6.427
| |  P99| 96ms| 189ms | 93ms | 96.624
| SessionStore.Save |  Avg| 44ms| 60ms | 16ms | 36.102
| |  P99| 473ms| 554ms | 81ms | 17.132
| SessionStore.UpdateLastActivityAt |  Avg| 10ms| 19ms | 9ms | 90.249
| |  P99| 87ms| 171ms | 84ms | 96.359
| StatusStore.Get |  Avg| 28ms| 35ms | 7ms | 25.434
| |  P99| 361ms| 431ms | 70ms | 19.385
| StatusStore.GetByIds |  Avg| 87ms| 104ms | 17ms | 19.453
| |  P99| 1.024s| 973ms | -51ms | -4.982
| StatusStore.SaveOrUpdate |  Avg| 67ms| 101ms | 34ms | 50.499
| |  P99| 915ms| 1.757s | 842ms | 91.980
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 12ms| 49ms | 37ms | 314.601
| |  P99| 86ms| 243ms | 157ms | 182.558
| StatusStore.UpdateLastActivityAt |  Avg| 11ms| 22ms | 11ms | 99.584
| |  P99| 92ms| 206ms | 114ms | 123.580
| SystemStore.GetByName |  Avg| 5ms| 10ms | 5ms | 102.848
| |  P99| 78ms| 100ms | 22ms | 28.038
| TeamStore.Get |  Avg| 56ms| 70ms | 14ms | 24.911
| |  P99| 778ms| 779ms | 1ms | 0.129
| TeamStore.GetAllPage |  Avg| 46ms| 56ms | 10ms | 21.687
| |  P99| 526ms| 554ms | 28ms | 5.320
| TeamStore.GetByName |  Avg| 57ms| 58ms | 1ms | 1.749
| |  P99| 808ms| 577ms | -231ms | -28.592
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 50ms| 58ms | 8ms | 15.929
| |  P99| 632ms| 549ms | -83ms | -13.137
| TeamStore.GetMember |  Avg| 4ms| 6ms | 2ms | 45.991
| |  P99| 74ms| 94ms | 20ms | 27.146
| TeamStore.GetTeamsByUserId |  Avg| 50ms| 59ms | 9ms | 18.112
| |  P99| 638ms| 559ms | -79ms | -12.391
| TeamStore.GetTeamsForUser |  Avg| 43ms| 53ms | 10ms | 23.090
| |  P99| 485ms| 522ms | 37ms | 7.622
| TeamStore.SaveMember |  Avg| 116ms| 136ms | 20ms | 17.275
| |  P99| 494ms| 702ms | 208ms | 42.086
| ThreadStore.Get |  Avg| 118ms| 94ms | -24ms | -20.308
| |  P99| 2.1s| 943ms | -1.157s | -55.092
| ThreadStore.GetMembershipForUser |  Avg| 66ms| 73ms | 7ms | 10.591
| |  P99| 821ms| 787ms | -34ms | -4.140
| ThreadStore.GetTeamsUnreadForUser |  Avg| 85ms| 89ms | 4ms | 4.696
| |  P99| 997ms| 952ms | -45ms | -4.512
| ThreadStore.GetThreadFollowers |  Avg| 71ms| 78ms | 7ms | 9.921
| |  P99| 904ms| 852ms | -52ms | -5.749
| ThreadStore.GetThreadForUser |  Avg| 101ms| 110ms | 9ms | 8.946
| |  P99| 1.263s| 1s | -263ms | -20.818
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 84ms| 90ms | 6ms | 7.148
| |  P99| 981ms| 883ms | -98ms | -9.992
| ThreadStore.GetThreadsForUser |  Avg| 83ms| 94ms | 11ms | 13.313
| |  P99| 929ms| 892ms | -37ms | -3.983
| ThreadStore.GetTotalThreads |  Avg| 50ms| 58ms | 8ms | 16.111
| |  P99| 602ms| 570ms | -32ms | -5.317
| ThreadStore.GetTotalUnreadMentions |  Avg| 51ms| 59ms | 8ms | 15.781
| |  P99| 642ms| 645ms | 3ms | 0.467
| ThreadStore.GetTotalUnreadThreads |  Avg| 48ms| 58ms | 10ms | 20.996
| |  P99| 579ms| 567ms | -12ms | -2.071
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 50ms| 59ms | 9ms | 18.117
| |  P99| 610ms| 613ms | 3ms | 0.492
| ThreadStore.MaintainMembership |  Avg| 18ms| 38ms | 20ms | 108.732
| |  P99| 206ms| 249ms | 43ms | 20.852
| ThreadStore.MarkAllAsReadByChannels |  Avg| 10ms| 23ms | 13ms | 128.733
| |  P99| 96ms| 198ms | 102ms | 106.040
| ThreadStore.MarkAllAsReadByTeam |  Avg| 8ms| 38ms | 30ms | 358.144
| |  P99| 25ms| 99ms | 74ms | 301.426
| ThreadStore.MarkAsRead |  Avg| 10ms| 18ms | 8ms | 79.988
| |  P99| 84ms| 120ms | 36ms | 42.818
| ThreadStore.UpdateMembership |  Avg| 11ms| 20ms | 9ms | 82.676
| |  P99| 92ms| 179ms | 87ms | 94.873
| TokenStore.Cleanup |  Avg| 21ms| 20ms | -1ms | -4.834
| |  P99| 50ms| 50ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 47ms| 122ms | 75ms | 159.986
| |  P99| 428ms| 932ms | 504ms | 117.891
| UserStore.AutocompleteUsersInChannel |  Avg| 602ms| 613ms | 11ms | 1.828
| |  P99| 2.344s| 2.358s | 14ms | 0.597
| UserStore.Count |  Avg| 139ms| 323ms | 184ms | 132.248
| |  P99| 463ms| 970ms | 507ms | 109.620
| UserStore.Get |  Avg| 28ms| 34ms | 6ms | 21.814
| |  P99| 428ms| 457ms | 29ms | 6.778
| UserStore.GetAllProfiles |  Avg| 49ms| 55ms | 6ms | 12.301
| |  P99| 670ms| 615ms | -55ms | -8.209
| UserStore.GetAllProfilesInChannel |  Avg| 1.43s| 1.443s | 13ms | 0.909
| |  P99| 4.598s| 4.738s | 140ms | 3.045
| UserStore.GetByUsername |  Avg| 96ms| 80ms | -16ms | -16.690
| |  P99| 882ms| 750ms | -132ms | -14.968
| UserStore.GetForLogin |  Avg| 36ms| 47ms | 11ms | 30.880
| |  P99| 443ms| 495ms | 52ms | 11.750
| UserStore.GetMany |  Avg| 54ms| 65ms | 11ms | 20.391
| |  P99| 237ms| 417ms | 180ms | 75.948
| UserStore.GetProfileByIds |  Avg| 43ms| 59ms | 16ms | 37.130
| |  P99| 540ms| 652ms | 112ms | 20.758
| UserStore.GetProfilesByUsernames |  Avg| 48ms| 66ms | 18ms | 37.872
| |  P99| 495ms| 661ms | 166ms | 33.524
| UserStore.GetProfilesInChannel |  Avg| 108ms| 267ms | 159ms | 147.182
| |  P99| 248ms| 980ms | 732ms | 295.458
| UserStore.GetUnreadCount |  Avg| 62ms| 66ms | 4ms | 6.455
| |  P99| 870ms| 808ms | -62ms | -7.129
| UserStore.GetUnreadCountForChannel |  Avg| 49ms| 0s | -49ms | -99.959
| |  P99| 635ms| 0s | -635ms | -99.978
| UserStore.IsEmpty |  Avg| 21ms| 26ms | 5ms | 24.245
| |  P99| 331ms| 368ms | 37ms | 11.163
| UserStore.Save |  Avg| 87ms| 104ms | 17ms | 19.485
| |  P99| 333ms| 463ms | 130ms | 38.987
| UserStore.Search |  Avg| 205ms| 214ms | 9ms | 4.387
| |  P99| 1.384s| 1.481s | 97ms | 7.010
| UserStore.Update |  Avg| 25ms| 40ms | 15ms | 58.897
| |  P99| 227ms| 246ms | 19ms | 8.378
| UserStore.UpdateFailedPasswordAttempts |  Avg| 9ms| 15ms | 6ms | 64.055
| |  P99| 89ms| 172ms | 83ms | 92.885
| UserStore.UpdateUpdateAt |  Avg| 7ms| 11ms | 4ms | 57.643
| |  P99| 67ms| 98ms | 31ms | 46.328
| UserTermsOfServiceStore.GetByUser |  Avg| 44ms| 56ms | 12ms | 26.991
| |  P99| 494ms| 549ms | 55ms | 11.128
| WebhookStore.GetOutgoingByTeam |  Avg| 74ms| 85ms | 11ms | 14.874
| |  P99| 856ms| 831ms | -25ms | -2.919
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 1.476s| 1.661s | 185ms | 12.534
| | P99| 9.275s| 8.725s | -550ms | -5.930
| addTeamMember | Avg| 2.694s| 2.985s | 291ms | 10.801
| | P99| 10s| 10s | 0s | 0.000
| autocompleteChannelsForTeamForSearch | Avg| 489ms| 480ms | -9ms | -1.840
| | P99| 3.508s| 2.467s | -1.041s | -29.674
| autocompleteUsers | Avg| 492ms| 501ms | 9ms | 1.829
| | P99| 2.315s| 2.335s | 20ms | 0.864
| createCategoryForTeamForUser | Avg| 203ms| 128ms | -75ms | -37.009
| | P99| 985ms| 483ms | -502ms | -50.964
| createChannel | Avg| 112ms| 219ms | 107ms | 95.620
| | P99| 248ms| 2.245s | 1.997s | 806.479
| createDirectChannel | Avg| 717ms| 1.1s | 383ms | 53.443
| | P99| 4.178s| 4.494s | 316ms | 7.564
| createGroupChannel | Avg| 1.334s| 1.987s | 653ms | 48.932
| | P99| 4.819s| 8.961s | 4.142s | 85.950
| createPost | Avg| 3.61s| 4.164s | 554ms | 15.345
| | P99| 10s| 10s | 0s | 0.000
| createUser | Avg| 184ms| 233ms | 49ms | 26.684
| | P99| 961ms| 1.468s | 507ms | 52.771
| deletePost | Avg| 384ms| 405ms | 21ms | 5.472
| | P99| 2.388s| 2.38s | -8ms | -0.335
| followThreadByUser | Avg| 147ms| 283ms | 136ms | 92.226
| | P99| 850ms| 1.945s | 1.095s | 128.819
| getAllTeams | Avg| 47ms| 58ms | 11ms | 23.212
| | P99| 539ms| 573ms | 34ms | 6.310
| getCategoriesForTeamForUser | Avg| 117ms| 131ms | 14ms | 12.008
| | P99| 1.226s| 1.237s | 11ms | 0.897
| getChannel | Avg| 100ms| 152ms | 52ms | 51.978
| | P99| 984ms| 1.69s | 706ms | 71.713
| getChannelMember | Avg| 57ms| 77ms | 20ms | 34.804
| | P99| 606ms| 745ms | 139ms | 22.933
| getChannelMembers | Avg| 58ms| 215ms | 157ms | 271.559
| | P99| 244ms| 249ms | 5ms | 2.049
| getChannelMembersForTeamForUser | Avg| 71ms| 80ms | 9ms | 12.684
| | P99| 860ms| 828ms | -32ms | -3.719
| getChannelStats | Avg| 83ms| 107ms | 24ms | 28.963
| | P99| 985ms| 1.634s | 649ms | 65.872
| getChannelUnread | Avg| 93ms| 91ms | -2ms | -2.151
| | P99| 912ms| 798ms | -114ms | -12.499
| getChannelsForTeamForUser | Avg| 76ms| 86ms | 10ms | 13.088
| | P99| 874ms| 862ms | -12ms | -1.373
| getChannelsForUser | Avg| 80ms| 86ms | 6ms | 7.483
| | P99| 826ms| 749ms | -77ms | -9.317
| getClientConfig | Avg| 15ms| 28ms | 13ms | 87.070
| | P99| 219ms| 291ms | 72ms | 32.842
| getFilePreview | Avg| 114ms| 168ms | 54ms | 47.398
| | P99| 860ms| 994ms | 134ms | 15.586
| getFileThumbnail | Avg| 109ms| 165ms | 56ms | 51.318
| | P99| 874ms| 1.108s | 234ms | 26.783
| getPostThread | Avg| 489ms| 488ms | -1ms | -0.205
| | P99| 4.501s| 3.784s | -717ms | -15.929
| getPostsForChannel | Avg| 3.361s| 1.075s | -2.286s | -68.017
| | P99| 10s| 10s | 0s | 0.000
| getPostsForChannelAroundLastUnread | Avg| 300ms| 267ms | -33ms | -11.011
| | P99| 3.724s| 2.395s | -1.329s | -35.685
| getPreferences | Avg| 55ms| 64ms | 9ms | 16.387
| | P99| 679ms| 623ms | -56ms | -8.249
| getProfileImage | Avg| 88ms| 84ms | -4ms | -4.555
| | P99| 472ms| 478ms | 6ms | 1.272
| getPublicChannelsForTeam | Avg| 109ms| 102ms | -7ms | -6.434
| | P99| 1.125s| 804ms | -321ms | -28.541
| getTeamMember | Avg| 15ms| 24ms | 9ms | 60.344
| | P99| 164ms| 236ms | 72ms | 43.851
| getTeamMembersForUser | Avg| 45ms| 56ms | 11ms | 24.549
| | P99| 488ms| 548ms | 60ms | 12.295
| getTeamsForUser | Avg| 50ms| 59ms | 9ms | 18.068
| | P99| 638ms| 563ms | -75ms | -11.762
| getTeamsUnreadForUser | Avg| 95ms| 103ms | 8ms | 8.397
| | P99| 1.221s| 1.006s | -215ms | -17.609
| getThreadsForUser | Avg| 89ms| 98ms | 9ms | 10.068
| | P99| 994ms| 943ms | -51ms | -5.129
| getUser | Avg| 58ms| 76ms | 18ms | 30.811
| | P99| 727ms| 758ms | 31ms | 4.262
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 2ms| 3ms | 1ms | 58.929
| | P99| 24ms| 67ms | 43ms | 177.552
| getUsers | Avg| 60ms| 72ms | 12ms | 20.124
| | P99| 805ms| 788ms | -17ms | -2.112
| getUsersByIds | Avg| 7ms| 9ms | 2ms | 28.837
| | P99| 140ms| 209ms | 69ms | 49.364
| getUsersByNames | Avg| 48ms| 67ms | 19ms | 39.311
| | P99| 498ms| 680ms | 182ms | 36.514
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| login | Avg| 223ms| 312ms | 89ms | 39.915
| | P99| 2.099s| 2.393s | 294ms | 14.008
| logout | Avg| 207ms| 319ms | 112ms | 54.153
| | P99| 925ms| 966ms | 41ms | 4.432
| patchPost | Avg| 2.82s| 3.51s | 690ms | 24.465
| | P99| 9.248s| 10s | 752ms | 8.132
| removeUserCustomStatus | Avg| 400ms| 468ms | 68ms | 17.016
| | P99| 2.113s| 2.332s | 219ms | 10.367
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 253ms| 327ms | 74ms | 29.293
| | P99| 2.336s| 2.369s | 33ms | 1.413
| searchAllChannels | Avg| 321ms| 362ms | 41ms | 12.759
| | P99| 6.06s| 5.148s | -912ms | -15.049
| searchGroupChannels | Avg| 80ms| 101ms | 21ms | 26.194
| | P99| 882ms| 942ms | 60ms | 6.805
| searchPostsInTeam | Avg| 529ms| 421ms | -108ms | -20.421
| | P99| 8.38s| 4.843s | -3.537s | -42.207
| searchUsers | Avg| 209ms| 218ms | 9ms | 4.316
| | P99| 1.404s| 1.53s | 126ms | 8.973
| setPostReminder | Avg| 450ms| 291ms | -159ms | -35.368
| | P99| 2.369s| 1.93s | -439ms | -18.533
| unfollowThreadByUser | Avg| 270ms| 220ms | -50ms | -18.522
| | P99| 3.151s| 970ms | -2.181s | -69.224
| updateCategoriesForTeamForUser | Avg| 531ms| 704ms | 173ms | 32.596
| | P99| 2.393s| 2.452s | 59ms | 2.466
| updatePreferences | Avg| 37ms| 74ms | 37ms | 98.982
| | P99| 278ms| 451ms | 173ms | 62.239
| updateReadStateAllThreadsByUser | Avg| 8ms| 38ms | 30ms | 353.280
| | P99| 25ms| 99ms | 74ms | 301.426
| updateReadStateThreadByUser | Avg| 601ms| 675ms | 74ms | 12.308
| | P99| 4.706s| 4.412s | -294ms | -6.247
| updateUserCustomStatus | Avg| 608ms| 679ms | 71ms | 11.684
| | P99| 5.826s| 2.428s | -3.398s | -58.325
| uploadFileStream | Avg| 529ms| 591ms | 62ms | 11.728
| | P99| 2.096s| 2.37s | 274ms | 13.073
| viewChannel | Avg| 241ms| 206ms | -35ms | -14.521
| | P99| 2.33s| 1.889s | -441ms | -18.928
