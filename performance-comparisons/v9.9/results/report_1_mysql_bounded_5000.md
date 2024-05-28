### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostStore.AnalyticsPostCount | avg | 1ms | 188ms | 187ms | 21452.90
| UserStore.GetMany | avg | 1ms | 11ms | 10ms | 1385.36
| StatusStore.GetByIds | avg | 1ms | 3ms | 2ms | 233.37
| PostStore.GetPostsAfter | avg | 3ms | 6ms | 3ms | 108.01
| PostPriorityStore.GetForPost | avg | 3ms | 5ms | 2ms | 64.32
| ChannelStore.AnalyticsTypeCount | avg | 4ms | 6ms | 2ms | 55.43
| PostStore.SearchPostsForUser | avg | 45ms | 70ms | 25ms | 55.28
| ChannelStore.Save | avg | 11ms | 17ms | 6ms | 53.98
| ChannelStore.GetPublicChannelsForTeam | avg | 9ms | 14ms | 5ms | 53.43
| ChannelStore.UpdateSidebarCategories | avg | 34ms | 40ms | 6ms | 17.74
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostStore.AnalyticsPostCount | p99 | 5ms | 249ms | 244ms | 4924.77
| StatusStore.GetByIds | p99 | 5ms | 59ms | 54ms | 1085.23
| UserStore.GetMany | p99 | 5ms | 49ms | 44ms | 888.80
| PostStore.GetPostsAfter | p99 | 21ms | 196ms | 175ms | 817.75
| ComplianceStore.MessageExport | p99 | 5ms | 44ms | 39ms | 787.88
| ChannelStore.Save | p99 | 46ms | 368ms | 322ms | 700.01
| ChannelStore.AnalyticsTypeCount | p99 | 10ms | 48ms | 38ms | 391.75
| ChannelStore.GetPublicChannelsForTeam | p99 | 22ms | 105ms | 83ms | 379.87
| PostStore.SearchPostsForUser | p99 | 340ms | 1.435s | 1.095s | 322.06
| ChannelStore.UpdateSidebarCategories | p99 | 92ms | 220ms | 128ms | 138.38
| PostPriorityStore.GetForPost | p99 | 83ms | 189ms | 106ms | 127.72
| StatusStore.UpdateExpiredDNDStatuses | p99 | 10ms | 22ms | 12ms | 120.60
| LinkMetadataStore.Save | p99 | 9ms | 20ms | 11ms | 115.89
| SessionStore.Remove | p99 | 5ms | 9ms | 4ms | 80.81
| PostPersistentNotificationStore.Get | p99 | 5ms | 9ms | 4ms | 80.81
| PostStore.Update | p99 | 25ms | 43ms | 18ms | 72.43
| ChannelStore.GetChannelUnread | p99 | 5ms | 8ms | 3ms | 60.59
| PluginStore.List | p99 | 27ms | 41ms | 14ms | 52.34
| PostAcknowledgementStore.GetForPost | p99 | 91ms | 129ms | 38ms | 41.53
| ChannelStore.GetPinnedPostCount | p99 | 15ms | 21ms | 6ms | 39.50
| UserStore.Save | p99 | 100ms | 119ms | 19ms | 18.99
| ChannelStore.GetMember | p99 | 16ms | 19ms | 3ms | 18.68
| FileInfoStore.AttachToPost | p99 | 19ms | 22ms | 3ms | 15.98
| UserStore.GetByUsername | p99 | 97ms | 108ms | 11ms | 11.31
| UserStore.UpdateUpdateAt | p99 | 19ms | 21ms | 2ms | 10.43
| ChannelStore.AutocompleteInTeamForSearch | p99 | 848ms | 915ms | 67ms | 7.90
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 91ms | 96ms | 5ms | 5.48
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| SystemStore.SaveOrUpdate | avg | 3ms | 0s | -3ms | -104.84
| SystemStore.PermanentDeleteByName | avg | 3ms | 0s | -3ms | -104.14
| UserStore.GetUnreadCount | avg | 5ms | 2ms | -3ms | -65.97
| RetentionPolicyStore.GetAll | avg | 3ms | 1ms | -2ms | -65.86
| UserStore.GetByUsername | avg | 4ms | 2ms | -2ms | -55.45
| PluginStore.List | avg | 4ms | 2ms | -2ms | -54.79
| ChannelStore.SearchGroupChannels | avg | 4ms | 2ms | -2ms | -50.56
| StatusStore.SaveOrUpdate | avg | 37ms | 20ms | -17ms | -45.86
| ChannelStore.Get | avg | 5ms | 3ms | -2ms | -42.86
| ChannelStore.GetChannelsByUser | avg | 17ms | 10ms | -7ms | -41.74
| ThreadStore.GetTotalUnreadMentions | avg | 5ms | 3ms | -2ms | -40.59
| SessionStore.GetLRUSessions | avg | 8ms | 5ms | -3ms | -39.96
| ThreadStore.GetTotalUnreadThreads | avg | 5ms | 3ms | -2ms | -37.76
| GroupStore.AdminRoleGroupsForSyncableMember | avg | 5ms | 3ms | -2ms | -36.89
| PostStore.GetEtag | avg | 6ms | 4ms | -2ms | -35.81
| ThreadStore.GetTotalUnreadUrgentMentions | avg | 6ms | 4ms | -2ms | -35.77
| ChannelStore.GetSidebarCategoriesForTeamForUser | avg | 20ms | 13ms | -7ms | -34.64
| ChannelStore.GetMemberLastViewedAt | avg | 6ms | 4ms | -2ms | -34.52
| TeamStore.GetChannelUnreadsForAllTeams | avg | 6ms | 4ms | -2ms | -32.28
| ChannelStore.GetGuestCount | avg | 9ms | 6ms | -3ms | -31.63
| TeamStore.GetTeamsForUser | avg | 6ms | 4ms | -2ms | -31.13
| ThreadStore.GetTeamsUnreadForUser | avg | 7ms | 5ms | -2ms | -30.12
| UserTermsOfServiceStore.GetByUser | avg | 7ms | 5ms | -2ms | -29.11
| GroupStore.GetByName | avg | 7ms | 5ms | -2ms | -28.06
| ChannelStore.GetTeamChannels | avg | 42ms | 31ms | -11ms | -26.01
| UserStore.GetForLogin | avg | 8ms | 6ms | -2ms | -25.20
| PostStore.GetPosts | avg | 9ms | 7ms | -2ms | -23.04
| PreferenceStore.GetAll | avg | 9ms | 7ms | -2ms | -21.75
| UserStore.Count | avg | 121ms | 96ms | -25ms | -20.61
| SessionStore.Get | avg | 10ms | 8ms | -2ms | -20.01
| ChannelStore.CreateDirectChannel | avg | 27ms | 22ms | -5ms | -18.72
| ChannelStore.SaveMember | avg | 49ms | 40ms | -9ms | -18.47
| SessionStore.Save | avg | 11ms | 9ms | -2ms | -17.75
| UserStore.AnalyticsActiveCount | avg | 207ms | 174ms | -33ms | -15.97
| ChannelStore.GetMemberCount | avg | 184ms | 158ms | -26ms | -14.12
| UserStore.GetAllProfilesInChannel | avg | 511ms | 454ms | -57ms | -11.15
| ChannelStore.CreateInitialSidebarCategories | avg | 25ms | 23ms | -2ms | -7.85
| TeamStore.GetTotalMemberCount | avg | 118ms | 110ms | -8ms | -6.79
| ChannelMemberHistoryStore.GetUsersInChannelDuring | avg | 274ms | 260ms | -14ms | -5.11
| UserStore.AutocompleteUsersInChannel | avg | 199ms | 194ms | -5ms | -2.51
| UserStore.Search | avg | 89ms | 87ms | -2ms | -2.24
| ChannelStore.Autocomplete | avg | 1.549s | 1.517s | -32ms | -2.07
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| SchemeStore.GetAllPage | p99 | 5ms | 0s | -5ms | -101.01
| SystemStore.PermanentDeleteByName | p99 | 5ms | 0s | -5ms | -101.01
| SystemStore.SaveOrUpdate | p99 | 5ms | 0s | -5ms | -100.98
| JobStore.GetNewestJobByStatusesAndType | p99 | 45ms | 5ms | -40ms | -89.89
| UserStore.Get | p99 | 23ms | 5ms | -18ms | -77.17
| UserAccessTokenStore.GetByToken | p99 | 19ms | 5ms | -14ms | -74.86
| UserStore.Update | p99 | 38ms | 10ms | -28ms | -72.74
| UserStore.GetUnreadCount | p99 | 88ms | 25ms | -63ms | -71.57
| ChannelStore.SearchGroupChannels | p99 | 110ms | 41ms | -69ms | -62.53
| PostStore.SetPostReminder | p99 | 25ms | 10ms | -15ms | -61.10
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 25ms | 10ms | -15ms | -60.30
| JobStore.UpdateStatus | p99 | 19ms | 8ms | -11ms | -59.29
| ThreadStore.GetThreadUnreadReplyCount | p99 | 21ms | 9ms | -12ms | -57.85
| RetentionPolicyStore.GetAll | p99 | 10ms | 5ms | -5ms | -50.76
| JobStore.GetAllByStatus | p99 | 115ms | 58ms | -57ms | -49.49
| StatusStore.SaveOrUpdate | p99 | 456ms | 235ms | -221ms | -48.42
| SessionStore.Save | p99 | 180ms | 100ms | -80ms | -44.36
| FileInfoStore.Get | p99 | 23ms | 13ms | -10ms | -43.74
| PostStore.GetPostsByThread | p99 | 14ms | 8ms | -6ms | -42.63
| UserStore.Count | p99 | 420ms | 248ms | -172ms | -40.95
| ReactionStore.GetForPost | p99 | 44ms | 26ms | -18ms | -40.72
| ChannelStore.GetMembersForUser | p99 | 86ms | 51ms | -35ms | -40.69
| ChannelStore.GetAllChannelMembersForUser | p99 | 79ms | 47ms | -32ms | -40.68
| GroupStore.GetGroups | p99 | 88ms | 55ms | -33ms | -37.71
| PostPriorityStore.GetForPosts | p99 | 66ms | 41ms | -25ms | -37.63
| TeamStore.GetTeamsForUser | p99 | 146ms | 92ms | -54ms | -37.07
| PostAcknowledgementStore.GetForPosts | p99 | 59ms | 37ms | -22ms | -36.98
| ThreadStore.GetMembershipForUser | p99 | 46ms | 29ms | -17ms | -36.61
| ChannelStore.GetByName | p99 | 153ms | 98ms | -55ms | -35.98
| ChannelStore.Get | p99 | 131ms | 84ms | -47ms | -35.86
| ThreadStore.GetTeamsUnreadForUser | p99 | 139ms | 89ms | -50ms | -35.86
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 137ms | 90ms | -47ms | -34.34
| ChannelStore.CreateDirectChannel | p99 | 411ms | 270ms | -141ms | -34.32
| TeamStore.GetAllPage | p99 | 146ms | 97ms | -49ms | -33.55
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 371ms | 247ms | -124ms | -33.42
| ChannelStore.GetFileCount | p99 | 90ms | 60ms | -30ms | -33.40
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 123ms | 82ms | -41ms | -33.32
| UserStore.GetProfilesByUsernames | p99 | 58ms | 39ms | -19ms | -32.88
| PostStore.GetPosts | p99 | 133ms | 91ms | -42ms | -31.64
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | p99 | 48ms | 33ms | -15ms | -31.16
| PostStore.GetPostsBefore | p99 | 71ms | 50ms | -21ms | -29.75
| ThreadStore.GetThreadForUser | p99 | 44ms | 31ms | -13ms | -29.35
| UserStore.AutocompleteUsersInChannel | p99 | 772ms | 546ms | -226ms | -29.27
| ChannelStore.CreateInitialSidebarCategories | p99 | 196ms | 140ms | -56ms | -28.50
| PostStore.GetEtag | p99 | 141ms | 101ms | -40ms | -28.31
| ChannelStore.GetMemberLastViewedAt | p99 | 124ms | 89ms | -35ms | -28.17
| FileInfoStore.Save | p99 | 14ms | 10ms | -4ms | -28.08
| PostPersistentNotificationStore.GetSingle | p99 | 43ms | 31ms | -12ms | -27.75
| ThreadStore.GetTotalThreads | p99 | 112ms | 81ms | -31ms | -27.66
| ChannelStore.GetChannelsByUser | p99 | 226ms | 165ms | -61ms | -27.03
| ChannelStore.GetChannels | p99 | 98ms | 72ms | -26ms | -26.56
| SessionStore.Get | p99 | 178ms | 132ms | -46ms | -25.91
| ThreadStore.GetThreadsForUser | p99 | 74ms | 55ms | -19ms | -25.83
| SessionStore.GetLRUSessions | p99 | 183ms | 137ms | -46ms | -25.20
| ChannelStore.GetGuestCount | p99 | 205ms | 154ms | -51ms | -24.87
| UserTermsOfServiceStore.GetByUser | p99 | 162ms | 122ms | -40ms | -24.67
| TeamStore.Get | p99 | 45ms | 34ms | -11ms | -24.63
| ChannelStore.GetAllChannelMemberIdsByChannelId | p99 | 104ms | 79ms | -25ms | -24.10
| UserStore.Search | p99 | 384ms | 292ms | -92ms | -23.97
| PreferenceStore.Get | p99 | 50ms | 38ms | -12ms | -23.87
| WebhookStore.GetOutgoingByTeam | p99 | 50ms | 38ms | -12ms | -23.82
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 99ms | 76ms | -23ms | -23.24
| ThreadStore.GetTotalUnreadThreads | p99 | 105ms | 81ms | -24ms | -22.80
| UserStore.GetForLogin | p99 | 181ms | 141ms | -40ms | -22.12
| StatusStore.Get | p99 | 118ms | 92ms | -26ms | -22.11
| GroupStore.GetByName | p99 | 163ms | 127ms | -36ms | -22.02
| ChannelStore.GetMemberCount | p99 | 859ms | 675ms | -184ms | -21.41
| EmojiStore.GetByName | p99 | 45ms | 36ms | -9ms | -19.82
| ChannelStore.GetMemberForPost | p99 | 46ms | 37ms | -9ms | -19.42
| ThreadStore.GetThreadFollowers | p99 | 48ms | 39ms | -9ms | -18.78
| ThreadStore.GetTotalUnreadMentions | p99 | 100ms | 82ms | -18ms | -18.02
| UserStore.IsEmpty | p99 | 91ms | 75ms | -16ms | -17.56
| ChannelStore.SaveMember | p99 | 475ms | 403ms | -72ms | -15.14
| PreferenceStore.GetAll | p99 | 183ms | 157ms | -26ms | -14.19
| PostStore.GetPostsSince | p99 | 90ms | 79ms | -11ms | -12.22
| UserStore.GetAllProfilesInChannel | p99 | 2.322s | 2.065s | -257ms | -11.07
| UserStore.GetAllProfiles | p99 | 96ms | 87ms | -9ms | -9.33
| UserStore.UpdateFailedPasswordAttempts | p99 | 22ms | 20ms | -2ms | -9.10
| TeamStore.GetTeamsByUserId | p99 | 122ms | 112ms | -10ms | -8.22
| ProductNoticesStore.View | p99 | 109ms | 106ms | -3ms | -2.76
| ChannelStore.Autocomplete | p99 | 5.056s | 4.942s | -114ms | -2.25
| TeamStore.SaveMember | p99 | 249ms | 246ms | -3ms | -1.21
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getPublicChannelsForTeam | avg | 10ms | 15ms | 5ms | 47.84
| searchPostsInTeam | avg | 54ms | 75ms | 21ms | 39.25
| createDirectChannel | avg | 173ms | 201ms | 28ms | 16.17
| updateCategoriesForTeamForUser | avg | 43ms | 49ms | 6ms | 14.03
| createGroupChannel | avg | 255ms | 283ms | 28ms | 10.99
| patchPost | avg | 20ms | 22ms | 2ms | 10.03
| removeUserCustomStatus | avg | 115ms | 125ms | 10ms | 8.71
| createUser | avg | 118ms | 122ms | 4ms | 3.38
| getAnalytics | avg | 188ms | 192ms | 4ms | 2.13
| uploadFileStream | avg | 357ms | 363ms | 6ms | 1.68
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getPublicChannelsForTeam | p99 | 25ms | 105ms | 80ms | 324.30
| searchPostsInTeam | p99 | 494ms | 1.435s | 941ms | 190.59
| updateCategoriesForTeamForUser | p99 | 98ms | 235ms | 137ms | 140.50
| createGroupChannel | p99 | 775ms | 1.765s | 990ms | 127.75
| getChannelUnread | p99 | 5ms | 8ms | 3ms | 60.59
| patchPost | p99 | 43ms | 50ms | 7ms | 16.36
| createDirectChannel | p99 | 499ms | 565ms | 66ms | 13.22
| autocompleteChannelsForTeamForSearch | p99 | 848ms | 915ms | 67ms | 7.90
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| searchGroupChannels | avg | 4ms | 2ms | -2ms | -49.82
| getFilteredUsersStats | avg | 135ms | 68ms | -67ms | -49.78
| getChannelsForUser | avg | 17ms | 11ms | -6ms | -34.73
| getTeamsUnreadForUser | avg | 10ms | 7ms | -3ms | -29.96
| getCategoriesForTeamForUser | avg | 20ms | 14ms | -6ms | -29.37
| getAllTeams | avg | 7ms | 5ms | -2ms | -27.42
| getPostsForChannelAroundLastUnread | avg | 38ms | 28ms | -10ms | -26.49
| getTeamMembersForUser | avg | 8ms | 6ms | -2ms | -26.42
| saveReaction | avg | 9ms | 7ms | -2ms | -22.99
| getPreferences | avg | 9ms | 7ms | -2ms | -21.22
| getChannelMember | avg | 12ms | 10ms | -2ms | -16.52
| setPostReminder | avg | 13ms | 11ms | -2ms | -15.56
| getPostsForChannel | avg | 22ms | 19ms | -3ms | -13.73
| getProfileImage | avg | 88ms | 76ms | -12ms | -13.62
| getChannelStats | avg | 18ms | 16ms | -2ms | -11.10
| addTeamMember | avg | 1.394s | 1.252s | -142ms | -10.19
| createPost | avg | 389ms | 354ms | -35ms | -8.99
| searchUsers | avg | 91ms | 88ms | -3ms | -3.30
| addChannelMember | avg | 174ms | 169ms | -5ms | -2.87
| login | avg | 73ms | 71ms | -2ms | -2.74
| searchAllChannels | avg | 1.549s | 1.517s | -32ms | -2.07
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| searchGroupChannels | p99 | 110ms | 41ms | -69ms | -62.53
| followThreadByUser | p99 | 24ms | 10ms | -14ms | -57.68
| unfollowThreadByUser | p99 | 23ms | 10ms | -13ms | -56.77
| updateReadStateThreadByUser | p99 | 214ms | 98ms | -116ms | -54.18
| addChannelMember | p99 | 443ms | 250ms | -193ms | -43.61
| getTeamMembersForUser | p99 | 169ms | 99ms | -70ms | -41.32
| getAllTeams | p99 | 160ms | 102ms | -58ms | -36.27
| getCategoriesForTeamForUser | p99 | 373ms | 248ms | -125ms | -33.53
| getChannelMembersForTeamForUser | p99 | 90ms | 61ms | -29ms | -32.07
| getUsersByNames | p99 | 58ms | 40ms | -18ms | -31.14
| viewChannel | p99 | 132ms | 91ms | -41ms | -31.02
| getChannelsForTeamForUser | p99 | 132ms | 92ms | -40ms | -30.32
| getTeamMember | p99 | 7ms | 5ms | -2ms | -29.72
| searchUsers | p99 | 389ms | 291ms | -98ms | -25.22
| autocompleteUsers | p99 | 641ms | 490ms | -151ms | -23.55
| getTeamsUnreadForUser | p99 | 210ms | 162ms | -48ms | -22.83
| getThreadsForUser | p99 | 88ms | 68ms | -20ms | -22.78
| getChannel | p99 | 100ms | 78ms | -22ms | -22.11
| getPostsForChannel | p99 | 287ms | 233ms | -54ms | -18.80
| getChannelsForUser | p99 | 228ms | 186ms | -42ms | -18.39
| getProfileImage | p99 | 391ms | 322ms | -69ms | -17.64
| getPostsForChannelAroundLastUnread | p99 | 531ms | 440ms | -91ms | -17.13
| getChannelMember | p99 | 217ms | 181ms | -36ms | -16.56
| getPreferences | p99 | 185ms | 160ms | -25ms | -13.50
| saveReaction | p99 | 204ms | 178ms | -26ms | -12.72
| getChannelStats | p99 | 437ms | 386ms | -51ms | -11.67
| getUser | p99 | 181ms | 163ms | -18ms | -9.96
| getUsers | p99 | 92ms | 83ms | -9ms | -9.79
| getClientConfig | p99 | 54ms | 49ms | -5ms | -9.29
| getTeamsForUser | p99 | 122ms | 112ms | -10ms | -8.22
| login | p99 | 483ms | 444ms | -39ms | -8.08
| addTeamMember | p99 | 4.794s | 4.561s | -233ms | -4.86
| createPost | p99 | 2.323s | 2.215s | -108ms | -4.65
| createUser | p99 | 449ms | 429ms | -20ms | -4.46
| getFileThumbnail | p99 | 96ms | 93ms | -3ms | -3.14
| searchAllChannels | p99 | 5.056s | 4.942s | -114ms | -2.25
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 20ms| 20ms | 0s | 0.000
| BotStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelMemberHistoryStore.GetUsersInChannelDuring |  Avg| 274ms| 260ms | -14ms | -5.115
| |  P99| 498ms| 497ms | -1ms | -0.201
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 18ms| 19ms | 1ms | 5.674
| ChannelStore.AnalyticsTypeCount |  Avg| 4ms| 6ms | 2ms | 55.432
| |  P99| 10ms| 48ms | 38ms | 391.754
| ChannelStore.Autocomplete |  Avg| 1.549s| 1.517s | -32ms | -2.066
| |  P99| 5.056s| 4.942s | -114ms | -2.255
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 124ms| 125ms | 1ms | 0.805
| |  P99| 848ms| 915ms | 67ms | 7.904
| ChannelStore.CreateDirectChannel |  Avg| 27ms| 22ms | -5ms | -18.722
| |  P99| 411ms| 270ms | -141ms | -34.322
| ChannelStore.CreateInitialSidebarCategories |  Avg| 25ms| 23ms | -2ms | -7.853
| |  P99| 196ms| 140ms | -56ms | -28.503
| ChannelStore.Get |  Avg| 5ms| 3ms | -2ms | -42.858
| |  P99| 131ms| 84ms | -47ms | -35.863
| ChannelStore.GetAllChannelMemberIdsByChannelId |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 104ms| 79ms | -25ms | -24.102
| ChannelStore.GetAllChannelMembersForUser |  Avg| 9ms| 8ms | -1ms | -10.537
| |  P99| 79ms| 47ms | -32ms | -40.683
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 91ms| 96ms | 5ms | 5.475
| ChannelStore.GetByName |  Avg| 7ms| 6ms | -1ms | -13.356
| |  P99| 153ms| 98ms | -55ms | -35.980
| ChannelStore.GetChannelUnread |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 8ms | 3ms | 60.586
| ChannelStore.GetChannels |  Avg| 4ms| 3ms | -1ms | -23.699
| |  P99| 98ms| 72ms | -26ms | -26.559
| ChannelStore.GetChannelsByUser |  Avg| 17ms| 10ms | -7ms | -41.740
| |  P99| 226ms| 165ms | -61ms | -27.032
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 48ms| 33ms | -15ms | -31.161
| ChannelStore.GetFileCount |  Avg| 5ms| 4ms | -1ms | -18.666
| |  P99| 90ms| 60ms | -30ms | -33.404
| ChannelStore.GetGuestCount |  Avg| 9ms| 6ms | -3ms | -31.635
| |  P99| 205ms| 154ms | -51ms | -24.872
| ChannelStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 16ms| 19ms | 3ms | 18.677
| ChannelStore.GetMemberCount |  Avg| 184ms| 158ms | -26ms | -14.116
| |  P99| 859ms| 675ms | -184ms | -21.411
| ChannelStore.GetMemberForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 46ms| 37ms | -9ms | -19.415
| ChannelStore.GetMemberLastViewedAt |  Avg| 6ms| 4ms | -2ms | -34.522
| |  P99| 124ms| 89ms | -35ms | -28.174
| ChannelStore.GetMembersForUser |  Avg| 4ms| 3ms | -1ms | -25.557
| |  P99| 86ms| 51ms | -35ms | -40.694
| ChannelStore.GetMembersForUserWithPagination |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.GetPinnedPostCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 15ms| 21ms | 6ms | 39.501
| ChannelStore.GetPublicChannelsForTeam |  Avg| 9ms| 14ms | 5ms | 53.428
| |  P99| 22ms| 105ms | 83ms | 379.874
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 20ms| 13ms | -7ms | -34.636
| |  P99| 371ms| 247ms | -124ms | -33.423
| ChannelStore.GetSidebarCategory |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ChannelStore.GetTeamChannels |  Avg| 42ms| 31ms | -11ms | -26.012
| |  P99| 50ms| 50ms | 0s | 0.000
| ChannelStore.IncrementMentionCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ChannelStore.Save |  Avg| 11ms| 17ms | 6ms | 53.984
| |  P99| 46ms| 368ms | 322ms | 700.006
| ChannelStore.SaveMember |  Avg| 49ms| 40ms | -9ms | -18.469
| |  P99| 475ms| 403ms | -72ms | -15.144
| ChannelStore.SearchGroupChannels |  Avg| 4ms| 2ms | -2ms | -50.560
| |  P99| 110ms| 41ms | -69ms | -62.532
| ChannelStore.UpdateLastViewedAt |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 14ms| 14ms | 0s | 0.000
| ChannelStore.UpdateSidebarCategories |  Avg| 34ms| 40ms | 6ms | 17.738
| |  P99| 92ms| 220ms | 128ms | 138.380
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 12ms| 12ms | 0s | 0.000
| CommandWebhookStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ComplianceStore.MessageExport |  Avg| 1ms| 2ms | 1ms | 74.656
| |  P99| 5ms| 44ms | 39ms | 787.879
| DraftStore.Delete |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| EmojiStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 45ms| 36ms | -9ms | -19.819
| EmojiStore.GetMultipleByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.AttachToPost |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 19ms| 22ms | 3ms | 15.980
| FileInfoStore.Get |  Avg| 2ms| 1ms | -1ms | -64.518
| |  P99| 23ms| 13ms | -10ms | -43.745
| FileInfoStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| FileInfoStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 14ms| 10ms | -4ms | -28.081
| FileInfoStore.SetContent |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 5ms| 3ms | -2ms | -36.888
| |  P99| 99ms| 76ms | -23ms | -23.243
| GroupStore.GetByName |  Avg| 7ms| 5ms | -2ms | -28.064
| |  P99| 163ms| 127ms | -36ms | -22.025
| GroupStore.GetGroups |  Avg| 4ms| 3ms | -1ms | -26.767
| |  P99| 88ms| 55ms | -33ms | -37.713
| GroupStore.GetGroupsAssociatedToChannelsByTeam |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 18ms| 19ms | 1ms | 5.617
| JobStore.GetAllByStatus |  Avg| 3ms| 2ms | -1ms | -28.811
| |  P99| 115ms| 58ms | -57ms | -49.491
| JobStore.GetAllByTypePage |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.GetCountByStatusAndType |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 21ms| 20ms | -1ms | -4.728
| JobStore.GetNewestJobByStatusesAndType |  Avg| 3ms| 2ms | -1ms | -29.485
| |  P99| 45ms| 5ms | -40ms | -89.888
| JobStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.173
| JobStore.UpdateOptimistically |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 14.347
| JobStore.UpdateStatus |  Avg| 4ms| 3ms | -1ms | -26.837
| |  P99| 19ms| 8ms | -11ms | -59.293
| JobStore.UpdateStatusOptimistically |  Avg| 4ms| 3ms | -1ms | -27.912
| |  P99| 9ms| 8ms | -1ms | -10.770
| LicenseStore.GetAll |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 29ms| 28ms | -1ms | -3.475
| LinkMetadataStore.Save |  Avg| 3ms| 4ms | 1ms | 29.484
| |  P99| 9ms| 20ms | 11ms | 115.885
| PluginStore.Delete |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PluginStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PluginStore.List |  Avg| 4ms| 2ms | -2ms | -54.788
| |  P99| 27ms| 41ms | 14ms | 52.337
| PluginStore.SetWithOptions |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 23ms| 22ms | -1ms | -4.434
| PostAcknowledgementStore.GetForPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 91ms| 129ms | 38ms | 41.532
| PostAcknowledgementStore.GetForPosts |  Avg| 3ms| 2ms | -1ms | -30.579
| |  P99| 59ms| 37ms | -22ms | -36.980
| PostPersistentNotificationStore.DeleteExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.808
| PostPersistentNotificationStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 43ms| 31ms | -12ms | -27.746
| PostPriorityStore.GetForPost |  Avg| 3ms| 5ms | 2ms | 64.322
| |  P99| 83ms| 189ms | 106ms | 127.719
| PostPriorityStore.GetForPosts |  Avg| 3ms| 2ms | -1ms | -30.597
| |  P99| 66ms| 41ms | -25ms | -37.632
| PostStore.AnalyticsPostCount |  Avg| 1ms| 188ms | 187ms | 21452.901
| |  P99| 5ms| 249ms | 244ms | 4924.774
| PostStore.Delete |  Avg| 12ms| 13ms | 1ms | 8.201
| |  P99| 25ms| 25ms | 0s | 0.000
| PostStore.Get |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 50ms| 49ms | -1ms | -1.988
| PostStore.GetEtag |  Avg| 6ms| 4ms | -2ms | -35.814
| |  P99| 141ms| 101ms | -40ms | -28.315
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 13ms| 14ms | 1ms | 7.646
| PostStore.GetPostIdBeforeTime |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| PostStore.GetPostReminderMetadata |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostReminders |  Avg| 6ms| 7ms | 1ms | 15.866
| |  P99| 22ms| 22ms | 0s | 0.000
| PostStore.GetPosts |  Avg| 9ms| 7ms | -2ms | -23.039
| |  P99| 133ms| 91ms | -42ms | -31.641
| PostStore.GetPostsAfter |  Avg| 3ms| 6ms | 3ms | 108.005
| |  P99| 21ms| 196ms | 175ms | 817.750
| PostStore.GetPostsBefore |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 71ms| 50ms | -21ms | -29.751
| PostStore.GetPostsByThread |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 14ms| 8ms | -6ms | -42.631
| PostStore.GetPostsSince |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 90ms| 79ms | -11ms | -12.217
| PostStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 25ms| 24ms | -1ms | -3.976
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 48ms| 48ms | 0s | 0.000
| PostStore.SearchPostsForUser |  Avg| 45ms| 70ms | 25ms | 55.278
| |  P99| 340ms| 1.435s | 1.095s | 322.062
| PostStore.SetPostReminder |  Avg| 8ms| 7ms | -1ms | -12.034
| |  P99| 25ms| 10ms | -15ms | -61.098
| PostStore.Update |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 25ms| 43ms | 18ms | 72.435
| PreferenceStore.DeleteCategoryAndName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PreferenceStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 50ms| 38ms | -12ms | -23.868
| PreferenceStore.GetAll |  Avg| 9ms| 7ms | -2ms | -21.746
| |  P99| 183ms| 157ms | -26ms | -14.187
| PreferenceStore.Save |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 42ms| 42ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 38ms| 38ms | 0s | 0.000
| |  P99| 109ms| 106ms | -3ms | -2.762
| ReactionStore.GetForPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 44ms| 26ms | -18ms | -40.723
| RetentionPolicyStore.GetAll |  Avg| 3ms| 1ms | -2ms | -65.863
| |  P99| 10ms| 5ms | -5ms | -50.761
| RetentionPolicyStore.GetCount |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| RoleStore.ChannelHigherScopedPermissions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| RoleStore.GetByNames |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SchemeStore.GetAllPage |  Avg| 1ms| 0s | -1ms | -177.627
| |  P99| 5ms| 0s | -5ms | -101.010
| SessionStore.Get |  Avg| 10ms| 8ms | -2ms | -20.012
| |  P99| 178ms| 132ms | -46ms | -25.911
| SessionStore.GetLRUSessions |  Avg| 8ms| 5ms | -3ms | -39.960
| |  P99| 183ms| 137ms | -46ms | -25.201
| SessionStore.GetSessionsExpired |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 25ms| 10ms | -15ms | -60.297
| SessionStore.Remove |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.808
| SessionStore.Save |  Avg| 11ms| 9ms | -2ms | -17.752
| |  P99| 180ms| 100ms | -80ms | -44.364
| SessionStore.UpdateLastActivityAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.754
| StatusStore.Get |  Avg| 5ms| 4ms | -1ms | -18.655
| |  P99| 118ms| 92ms | -26ms | -22.114
| StatusStore.GetByIds |  Avg| 1ms| 3ms | 2ms | 233.373
| |  P99| 5ms| 59ms | 54ms | 1085.228
| StatusStore.SaveOrUpdate |  Avg| 37ms| 20ms | -17ms | -45.861
| |  P99| 456ms| 235ms | -221ms | -48.416
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 10ms| 22ms | 12ms | 120.603
| StatusStore.UpdateLastActivityAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| SystemStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 13ms| 13ms | 0s | 0.000
| SystemStore.PermanentDeleteByName |  Avg| 3ms| 0s | -3ms | -104.142
| |  P99| 5ms| 0s | -5ms | -101.010
| SystemStore.SaveOrUpdate |  Avg| 3ms| 0s | -3ms | -104.838
| |  P99| 5ms| 0s | -5ms | -100.979
| TeamStore.AnalyticsTeamCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 45ms| 34ms | -11ms | -24.627
| TeamStore.GetActiveMemberCount |  Avg| 149ms| 149ms | 0s | 0.000
| |  P99| 249ms| 249ms | 0s | 0.000
| TeamStore.GetAllPage |  Avg| 6ms| 5ms | -1ms | -15.423
| |  P99| 146ms| 97ms | -49ms | -33.551
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 6ms| 4ms | -2ms | -32.280
| |  P99| 137ms| 90ms | -47ms | -34.343
| TeamStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetTeamsByUserId |  Avg| 6ms| 5ms | -1ms | -16.028
| |  P99| 122ms| 112ms | -10ms | -8.223
| TeamStore.GetTeamsForUser |  Avg| 6ms| 4ms | -2ms | -31.127
| |  P99| 146ms| 92ms | -54ms | -37.070
| TeamStore.GetTotalMemberCount |  Avg| 118ms| 110ms | -8ms | -6.792
| |  P99| 249ms| 249ms | 0s | 0.000
| TeamStore.SaveMember |  Avg| 100ms| 99ms | -1ms | -0.996
| |  P99| 249ms| 246ms | -3ms | -1.206
| ThreadStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetMembershipForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 46ms| 29ms | -17ms | -36.613
| ThreadStore.GetTeamsUnreadForUser |  Avg| 7ms| 5ms | -2ms | -30.124
| |  P99| 139ms| 89ms | -50ms | -35.857
| ThreadStore.GetThreadFollowers |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 48ms| 39ms | -9ms | -18.777
| ThreadStore.GetThreadForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 44ms| 31ms | -13ms | -29.350
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 21ms| 9ms | -12ms | -57.855
| ThreadStore.GetThreadsForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 74ms| 55ms | -19ms | -25.833
| ThreadStore.GetTotalThreads |  Avg| 5ms| 4ms | -1ms | -18.760
| |  P99| 112ms| 81ms | -31ms | -27.662
| ThreadStore.GetTotalUnreadMentions |  Avg| 5ms| 3ms | -2ms | -40.595
| |  P99| 100ms| 82ms | -18ms | -18.017
| ThreadStore.GetTotalUnreadThreads |  Avg| 5ms| 3ms | -2ms | -37.762
| |  P99| 105ms| 81ms | -24ms | -22.801
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 6ms| 4ms | -2ms | -35.771
| |  P99| 123ms| 82ms | -41ms | -33.316
| ThreadStore.MaintainMembership |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 18ms| 18ms | 0s | 0.000
| ThreadStore.MarkAllAsReadByChannels |  Avg| 2ms| 3ms | 1ms | 40.750
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.MarkAsRead |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ThreadStore.UpdateMembership |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| TokenStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 19ms| 5ms | -14ms | -74.863
| UserStore.AnalyticsActiveCount |  Avg| 207ms| 174ms | -33ms | -15.973
| |  P99| 248ms| 248ms | 0s | 0.000
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AutocompleteUsersInChannel |  Avg| 199ms| 194ms | -5ms | -2.506
| |  P99| 772ms| 546ms | -226ms | -29.273
| UserStore.Count |  Avg| 121ms| 96ms | -25ms | -20.612
| |  P99| 420ms| 248ms | -172ms | -40.948
| UserStore.Get |  Avg| 2ms| 1ms | -1ms | -52.969
| |  P99| 23ms| 5ms | -18ms | -77.166
| UserStore.GetAllProfiles |  Avg| 7ms| 6ms | -1ms | -13.640
| |  P99| 96ms| 87ms | -9ms | -9.329
| UserStore.GetAllProfilesInChannel |  Avg| 511ms| 454ms | -57ms | -11.154
| |  P99| 2.322s| 2.065s | -257ms | -11.069
| UserStore.GetByUsername |  Avg| 4ms| 2ms | -2ms | -55.453
| |  P99| 97ms| 108ms | 11ms | 11.310
| UserStore.GetForLogin |  Avg| 8ms| 6ms | -2ms | -25.205
| |  P99| 181ms| 141ms | -40ms | -22.117
| UserStore.GetMany |  Avg| 1ms| 11ms | 10ms | 1385.362
| |  P99| 5ms| 49ms | 44ms | 888.801
| UserStore.GetProfileByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 11ms | 1ms | 10.079
| UserStore.GetProfilesByUsernames |  Avg| 3ms| 2ms | -1ms | -36.646
| |  P99| 58ms| 39ms | -19ms | -32.885
| UserStore.GetProfilesInChannel |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfilesNotInChannel |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetUnreadCount |  Avg| 5ms| 2ms | -3ms | -65.965
| |  P99| 88ms| 25ms | -63ms | -71.573
| UserStore.IsEmpty |  Avg| 4ms| 3ms | -1ms | -22.313
| |  P99| 91ms| 75ms | -16ms | -17.560
| UserStore.Save |  Avg| 68ms| 68ms | 0s | 0.000
| |  P99| 100ms| 119ms | 19ms | 18.992
| UserStore.Search |  Avg| 89ms| 87ms | -2ms | -2.236
| |  P99| 384ms| 292ms | -92ms | -23.965
| UserStore.Update |  Avg| 7ms| 6ms | -1ms | -15.243
| |  P99| 38ms| 10ms | -28ms | -72.736
| UserStore.UpdateFailedPasswordAttempts |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 22ms| 20ms | -2ms | -9.102
| UserStore.UpdateLastLogin |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 19ms| 19ms | 0s | 0.000
| UserStore.UpdateUpdateAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 19ms| 21ms | 2ms | 10.433
| UserTermsOfServiceStore.GetByUser |  Avg| 7ms| 5ms | -2ms | -29.107
| |  P99| 162ms| 122ms | -40ms | -24.668
| WebhookStore.GetOutgoingByTeam |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 50ms| 38ms | -12ms | -23.823
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 174ms| 169ms | -5ms | -2.870
| | P99| 443ms| 250ms | -193ms | -43.615
| addTeamMember | Avg| 1.394s| 1.252s | -142ms | -10.188
| | P99| 4.794s| 4.561s | -233ms | -4.860
| autocompleteChannelsForTeamForSearch | Avg| 124ms| 125ms | 1ms | 0.805
| | P99| 848ms| 915ms | 67ms | 7.904
| autocompleteUsers | Avg| 157ms| 156ms | -1ms | -0.637
| | P99| 641ms| 490ms | -151ms | -23.550
| createChannel | Avg| 228ms| 226ms | -2ms | -0.876
| | P99| 249ms| 249ms | 0s | 0.000
| createDirectChannel | Avg| 173ms| 201ms | 28ms | 16.173
| | P99| 499ms| 565ms | 66ms | 13.222
| createGroupChannel | Avg| 255ms| 283ms | 28ms | 10.995
| | P99| 775ms| 1.765s | 990ms | 127.752
| createPost | Avg| 389ms| 354ms | -35ms | -8.990
| | P99| 2.323s| 2.215s | -108ms | -4.648
| createUser | Avg| 118ms| 122ms | 4ms | 3.378
| | P99| 449ms| 429ms | -20ms | -4.456
| deletePost | Avg| 15ms| 16ms | 1ms | 6.806
| | P99| 25ms| 25ms | 0s | 0.000
| followThreadByUser | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 24ms| 10ms | -14ms | -57.676
| getAllTeams | Avg| 7ms| 5ms | -2ms | -27.420
| | P99| 160ms| 102ms | -58ms | -36.266
| getAnalytics | Avg| 188ms| 192ms | 4ms | 2.130
| | P99| 490ms| 492ms | 2ms | 0.408
| getCategoriesForTeamForUser | Avg| 20ms| 14ms | -6ms | -29.365
| | P99| 373ms| 248ms | -125ms | -33.534
| getChannel | Avg| 5ms| 4ms | -1ms | -20.162
| | P99| 100ms| 78ms | -22ms | -22.109
| getChannelMember | Avg| 12ms| 10ms | -2ms | -16.516
| | P99| 217ms| 181ms | -36ms | -16.564
| getChannelMembersForTeamForUser | Avg| 4ms| 3ms | -1ms | -23.192
| | P99| 90ms| 61ms | -29ms | -32.070
| getChannelStats | Avg| 18ms| 16ms | -2ms | -11.103
| | P99| 437ms| 386ms | -51ms | -11.666
| getChannelUnread | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 8ms | 3ms | 60.586
| getChannelsForTeamForUser | Avg| 5ms| 4ms | -1ms | -19.002
| | P99| 132ms| 92ms | -40ms | -30.315
| getChannelsForUser | Avg| 17ms| 11ms | -6ms | -34.730
| | P99| 228ms| 186ms | -42ms | -18.392
| getClientConfig | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 54ms| 49ms | -5ms | -9.294
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getFilePreview | Avg| 36ms| 36ms | 0s | 0.000
| | P99| 98ms| 97ms | -1ms | -1.017
| getFileThumbnail | Avg| 30ms| 29ms | -1ms | -3.344
| | P99| 96ms| 93ms | -3ms | -3.137
| getFilteredUsersStats | Avg| 135ms| 68ms | -67ms | -49.780
| | P99| 249ms| 247ms | -2ms | -0.805
| getJobsByType | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getPostThread | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 76ms| 76ms | 0s | 0.000
| getPostsForChannel | Avg| 22ms| 19ms | -3ms | -13.726
| | P99| 287ms| 233ms | -54ms | -18.800
| getPostsForChannelAroundLastUnread | Avg| 38ms| 28ms | -10ms | -26.492
| | P99| 531ms| 440ms | -91ms | -17.127
| getPreferences | Avg| 9ms| 7ms | -2ms | -21.219
| | P99| 185ms| 160ms | -25ms | -13.498
| getPrevTrialLicense | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getProfileImage | Avg| 88ms| 76ms | -12ms | -13.622
| | P99| 391ms| 322ms | -69ms | -17.644
| getPublicChannelsForTeam | Avg| 10ms| 15ms | 5ms | 47.840
| | P99| 25ms| 105ms | 80ms | 324.300
| getRolesByNames | Avg| 0s| 1ms | 1ms | 880.778
| | P99| 5ms| 5ms | 0s | 0.000
| getTeamMember | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 7ms| 5ms | -2ms | -29.725
| getTeamMembersForUser | Avg| 8ms| 6ms | -2ms | -26.422
| | P99| 169ms| 99ms | -70ms | -41.315
| getTeamStats | Avg| 149ms| 150ms | 1ms | 0.673
| | P99| 249ms| 249ms | 0s | 0.000
| getTeamsForUser | Avg| 6ms| 5ms | -1ms | -15.886
| | P99| 122ms| 112ms | -10ms | -8.221
| getTeamsUnreadForUser | Avg| 10ms| 7ms | -3ms | -29.959
| | P99| 210ms| 162ms | -48ms | -22.830
| getThreadsForUser | Avg| 4ms| 3ms | -1ms | -24.828
| | P99| 88ms| 68ms | -20ms | -22.775
| getUser | Avg| 8ms| 7ms | -1ms | -12.078
| | P99| 181ms| 163ms | -18ms | -9.957
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 92ms| 83ms | -9ms | -9.788
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsersByNames | Avg| 3ms| 2ms | -1ms | -35.031
| | P99| 58ms| 40ms | -18ms | -31.137
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| login | Avg| 73ms| 71ms | -2ms | -2.737
| | P99| 483ms| 444ms | -39ms | -8.082
| logout | Avg| 34ms| 33ms | -1ms | -2.918
| | P99| 50ms| 50ms | 0s | 0.000
| patchPost | Avg| 20ms| 22ms | 2ms | 10.028
| | P99| 43ms| 50ms | 7ms | 16.359
| removeUserCustomStatus | Avg| 115ms| 125ms | 10ms | 8.709
| | P99| 248ms| 248ms | 0s | 0.000
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 9ms| 7ms | -2ms | -22.986
| | P99| 204ms| 178ms | -26ms | -12.725
| searchAllChannels | Avg| 1.549s| 1.517s | -32ms | -2.066
| | P99| 5.056s| 4.942s | -114ms | -2.255
| searchGroupChannels | Avg| 4ms| 2ms | -2ms | -49.821
| | P99| 110ms| 41ms | -69ms | -62.532
| searchPostsInTeam | Avg| 54ms| 75ms | 21ms | 39.245
| | P99| 494ms| 1.435s | 941ms | 190.586
| searchUsers | Avg| 91ms| 88ms | -3ms | -3.303
| | P99| 389ms| 291ms | -98ms | -25.217
| setPostReminder | Avg| 13ms| 11ms | -2ms | -15.561
| | P99| 25ms| 25ms | 0s | 0.000
| unfollowThreadByUser | Avg| 8ms| 9ms | 1ms | 11.787
| | P99| 23ms| 10ms | -13ms | -56.770
| updateCategoriesForTeamForUser | Avg| 43ms| 49ms | 6ms | 14.025
| | P99| 98ms| 235ms | 137ms | 140.505
| updatePreferences | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 23ms| 23ms | 0s | 0.000
| updateReadStateThreadByUser | Avg| 21ms| 20ms | -1ms | -4.716
| | P99| 214ms| 98ms | -116ms | -54.178
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 357ms| 363ms | 6ms | 1.681
| | P99| 984ms| 984ms | 0s | 0.000
| upsertDraft | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| viewChannel | Avg| 11ms| 10ms | -1ms | -8.921
| | P99| 132ms| 91ms | -41ms | -31.017
