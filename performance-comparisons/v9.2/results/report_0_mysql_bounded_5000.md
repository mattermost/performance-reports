### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| UserStore.GetMany | avg | 1ms | 4ms | 3ms | 319.57
| ProductNoticesStore.ClearOldNotices | avg | 2ms | 6ms | 4ms | 181.36
| LinkMetadataStore.Save | avg | 2ms | 4ms | 2ms | 94.74
| UserStore.Search | avg | 28ms | 30ms | 2ms | 7.10
| ChannelStore.GetMembers | avg | 75ms | 80ms | 5ms | 6.62
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| UserStore.GetMany | p99 | 5ms | 24ms | 19ms | 383.84
| ChannelStore.GetSidebarCategory | p99 | 10ms | 39ms | 29ms | 293.10
| ChannelStore.GetPublicChannelsForTeam | p99 | 22ms | 58ms | 36ms | 166.69
| JobStore.GetAllByStatus | p99 | 5ms | 12ms | 7ms | 140.63
| UserStore.GetByUsername | p99 | 5ms | 11ms | 6ms | 121.21
| JobStore.Save | p99 | 10ms | 21ms | 11ms | 112.70
| ProductNoticesStore.ClearOldNotices | p99 | 5ms | 10ms | 5ms | 101.00
| JobStore.UpdateOptimistically | p99 | 10ms | 18ms | 8ms | 82.37
| BotStore.Get | p99 | 5ms | 9ms | 4ms | 80.81
| ChannelStore.GetChannelUnread | p99 | 5ms | 9ms | 4ms | 80.81
| ClusterDiscoveryStore.SetLastPingAt | p99 | 13ms | 19ms | 6ms | 45.11
| LinkMetadataStore.Save | p99 | 7ms | 10ms | 3ms | 41.02
| ChannelStore.UpdateSidebarChannelsByPreferences | p99 | 5ms | 7ms | 2ms | 40.08
| PostStore.Get | p99 | 10ms | 13ms | 3ms | 28.76
| ChannelStore.AutocompleteInTeamForSearch | p99 | 2.426s | 3.06s | 634ms | 26.13
| TeamStore.GetTeamsForUser | p99 | 11ms | 13ms | 2ms | 19.00
| StatusStore.SaveOrUpdate | p99 | 15ms | 17ms | 2ms | 13.42
| UserStore.AutocompleteUsersInChannel | p99 | 357ms | 367ms | 10ms | 2.80
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ThreadStore.MarkAllAsReadByTeam | avg | 2ms | 0s | -2ms | -97.47
| UserStore.GetUnreadCount | avg | 16ms | 12ms | -4ms | -25.56
| UserStore.GetAllProfiles | avg | 9ms | 7ms | -2ms | -22.82
| UserStore.Count | avg | 75ms | 63ms | -12ms | -15.92
| ChannelStore.UpdateSidebarCategories | avg | 35ms | 31ms | -4ms | -11.44
| PostStore.SearchPostsForUser | avg | 122ms | 118ms | -4ms | -3.27
| PostStore.AnalyticsPostCount | avg | 4.015s | 3.89s | -125ms | -3.11
| UserStore.GetAllProfilesInChannel | avg | 290ms | 286ms | -4ms | -1.38
| ChannelStore.AutocompleteInTeamForSearch | avg | 311ms | 307ms | -4ms | -1.29
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ThreadStore.MarkAllAsReadByTeam | p99 | 5ms | 0s | -5ms | -101.01
| PostPriorityStore.GetForPost | p99 | 24ms | 5ms | -19ms | -80.08
| PostAcknowledgementStore.GetForPost | p99 | 17ms | 5ms | -12ms | -68.77
| FileInfoStore.Save | p99 | 20ms | 10ms | -10ms | -50.58
| ChannelStore.Autocomplete | p99 | 337ms | 174ms | -163ms | -48.43
| PostPersistentNotificationStore.DeleteExpired | p99 | 9ms | 5ms | -4ms | -46.51
| RoleStore.ChannelHigherScopedPermissions | p99 | 9ms | 5ms | -4ms | -45.38
| ChannelStore.UpdateSidebarCategories | p99 | 91ms | 50ms | -41ms | -45.06
| JobStore.UpdateStatus | p99 | 18ms | 10ms | -8ms | -44.20
| ChannelStore.CreateDirectChannel | p99 | 73ms | 42ms | -31ms | -42.32
| PostStore.SearchPostsForUser | p99 | 832ms | 500ms | -332ms | -39.92
| JobStore.GetCountByStatusAndType | p99 | 8ms | 5ms | -3ms | -39.74
| ChannelStore.GetChannelsByUser | p99 | 8ms | 5ms | -3ms | -38.96
| TeamStore.GetAllPage | p99 | 16ms | 10ms | -6ms | -37.92
| FileInfoStore.SetContent | p99 | 39ms | 25ms | -14ms | -35.59
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 15ms | 10ms | -5ms | -34.43
| GroupStore.GetByName | p99 | 15ms | 10ms | -5ms | -32.69
| UserStore.Get | p99 | 7ms | 5ms | -2ms | -28.33
| ThreadStore.GetTotalUnreadMentions | p99 | 18ms | 13ms | -5ms | -28.00
| ThreadStore.GetThreadFollowers | p99 | 7ms | 5ms | -2ms | -27.22
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 7ms | 5ms | -2ms | -27.17
| ThreadStore.GetThreadForUser | p99 | 14ms | 11ms | -3ms | -21.52
| JobStore.GetNewestJobByStatusesAndType | p99 | 10ms | 8ms | -2ms | -19.42
| ThreadStore.GetTotalUnreadThreads | p99 | 11ms | 9ms | -2ms | -18.42
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 11ms | 9ms | -2ms | -18.33
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 11ms | 9ms | -2ms | -17.52
| UserStore.GetForLogin | p99 | 18ms | 15ms | -3ms | -16.93
| UserStore.GetProfileByIds | p99 | 12ms | 10ms | -2ms | -16.83
| StatusStore.UpdateLastActivityAt | p99 | 12ms | 10ms | -2ms | -16.75
| ThreadStore.GetTeamsUnreadForUser | p99 | 19ms | 16ms | -3ms | -16.12
| ChannelStore.CreateInitialSidebarCategories | p99 | 78ms | 66ms | -12ms | -15.34
| UserStore.GetUnreadCount | p99 | 648ms | 555ms | -93ms | -14.35
| PostStore.GetPostIdAfterTime | p99 | 16ms | 14ms | -2ms | -12.62
| SessionStore.Get | p99 | 34ms | 30ms | -4ms | -11.84
| ChannelStore.GetGuestCount | p99 | 21ms | 19ms | -2ms | -9.64
| UserStore.Save | p99 | 167ms | 153ms | -14ms | -8.40
| ChannelStore.Save | p99 | 73ms | 67ms | -6ms | -8.28
| ChannelStore.GetByName | p99 | 27ms | 25ms | -2ms | -7.44
| UserStore.GetAllProfiles | p99 | 223ms | 207ms | -16ms | -7.18
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 28ms | 26ms | -2ms | -7.05
| TeamStore.SaveMember | p99 | 153ms | 143ms | -10ms | -6.55
| ProductNoticesStore.View | p99 | 164ms | 160ms | -4ms | -2.45
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| patchPost | avg | 255ms | 711ms | 456ms | 179.17
| getPublicChannelsForTeam | avg | 10ms | 12ms | 2ms | 19.46
| createPost | avg | 308ms | 345ms | 37ms | 12.01
| logout | avg | 39ms | 42ms | 3ms | 7.71
| searchUsers | avg | 29ms | 31ms | 2ms | 6.89
| removeUserCustomStatus | avg | 129ms | 131ms | 2ms | 1.55
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getPublicChannelsForTeam | p99 | 25ms | 58ms | 33ms | 133.69
| updateCategoriesForTeamForUser | p99 | 97ms | 217ms | 120ms | 123.71
| logout | p99 | 50ms | 97ms | 47ms | 94.46
| getChannelUnread | p99 | 5ms | 9ms | 4ms | 80.81
| createPost | p99 | 1.523s | 2s | 477ms | 31.32
| autocompleteChannelsForTeamForSearch | p99 | 2.426s | 3.06s | 634ms | 26.13
| searchPostsInTeam | p99 | 874ms | 990ms | 116ms | 13.28
| getPostsForChannel | p99 | 130ms | 137ms | 7ms | 5.40
| autocompleteUsers | p99 | 307ms | 319ms | 12ms | 3.91
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| updateReadStateAllThreadsByUser | avg | 2ms | 0s | -2ms | -92.86
| getUsers | avg | 10ms | 8ms | -2ms | -19.16
| createGroupChannel | avg | 301ms | 278ms | -23ms | -7.63
| searchPostsInTeam | avg | 126ms | 121ms | -5ms | -3.95
| uploadFileStream | avg | 472ms | 455ms | -17ms | -3.60
| getProfileImage | avg | 107ms | 105ms | -2ms | -1.87
| addChannelMember | avg | 202ms | 199ms | -3ms | -1.49
| autocompleteChannelsForTeamForSearch | avg | 311ms | 307ms | -4ms | -1.29
| addTeamMember | avg | 880ms | 869ms | -11ms | -1.25
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| updateReadStateAllThreadsByUser | p99 | 5ms | 0s | -5ms | -101.01
| searchAllChannels | p99 | 337ms | 174ms | -163ms | -48.43
| deletePost | p99 | 47ms | 25ms | -22ms | -47.06
| getChannelsForUser | p99 | 8ms | 5ms | -3ms | -38.96
| updateUserCustomStatus | p99 | 375ms | 248ms | -127ms | -33.87
| getChannel | p99 | 10ms | 7ms | -3ms | -29.12
| uploadFileStream | p99 | 1.923s | 1.481s | -442ms | -22.98
| getAllTeams | p99 | 19ms | 16ms | -3ms | -15.43
| getUser | p99 | 23ms | 20ms | -3ms | -13.13
| getCategoriesForTeamForUser | p99 | 31ms | 27ms | -4ms | -12.89
| getTeamsUnreadForUser | p99 | 24ms | 21ms | -3ms | -12.57
| getChannelsForTeamForUser | p99 | 17ms | 15ms | -2ms | -11.88
| getTeamMembersForUser | p99 | 21ms | 19ms | -2ms | -9.46
| getPostsForChannelAroundLastUnread | p99 | 93ms | 86ms | -7ms | -7.53
| getUsers | p99 | 223ms | 208ms | -15ms | -6.72
| patchPost | p99 | 10s | 9.475s | -525ms | -5.25
| getChannelMember | p99 | 40ms | 38ms | -2ms | -5.01
| saveReaction | p99 | 45ms | 43ms | -2ms | -4.49
| getFilePreview | p99 | 202ms | 195ms | -7ms | -3.47
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| BotStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.808
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 21ms| 21ms | 0s | 0.000
| ChannelStore.Autocomplete |  Avg| 45ms| 44ms | -1ms | -2.199
| |  P99| 337ms| 174ms | -163ms | -48.427
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 311ms| 307ms | -4ms | -1.286
| |  P99| 2.426s| 3.06s | 634ms | 26.129
| ChannelStore.CreateDirectChannel |  Avg| 20ms| 20ms | 0s | 0.000
| |  P99| 73ms| 42ms | -31ms | -42.320
| ChannelStore.CreateInitialSidebarCategories |  Avg| 22ms| 21ms | -1ms | -4.629
| |  P99| 78ms| 66ms | -12ms | -15.338
| ChannelStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 6ms | -1ms | -15.032
| ChannelStore.GetAllChannelMembersForUser |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 20ms| 19ms | -1ms | -5.028
| |  P99| 88ms| 87ms | -1ms | -1.134
| ChannelStore.GetByName |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 27ms| 25ms | -2ms | -7.442
| ChannelStore.GetChannelUnread |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.808
| ChannelStore.GetChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.331
| ChannelStore.GetChannelsByUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 5ms | -3ms | -38.961
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetFileCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ChannelStore.GetGuestCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 21ms| 19ms | -2ms | -9.644
| ChannelStore.GetMember |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMemberCount |  Avg| 65ms| 64ms | -1ms | -1.531
| |  P99| 244ms| 244ms | 0s | 0.000
| ChannelStore.GetMemberForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMembers |  Avg| 75ms| 80ms | 5ms | 6.624
| |  P99| 248ms| 247ms | -1ms | -0.403
| ChannelStore.GetMembersForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 7ms | -1ms | -12.774
| ChannelStore.GetPinnedPostCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 7ms | -1ms | -13.206
| ChannelStore.GetPublicChannelsForTeam |  Avg| 9ms| 10ms | 1ms | 11.043
| |  P99| 22ms| 58ms | 36ms | 166.693
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 28ms| 26ms | -2ms | -7.053
| ChannelStore.GetSidebarCategory |  Avg| 5ms| 6ms | 1ms | 21.946
| |  P99| 10ms| 39ms | 29ms | 293.102
| ChannelStore.GetTeamChannels |  Avg| 25ms| 25ms | 0s | 0.000
| |  P99| 49ms| 49ms | 0s | 0.000
| ChannelStore.IncrementMentionCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 13ms| 13ms | 0s | 0.000
| ChannelStore.InvalidateAllChannelMembersForUser |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.InvalidateChannelByName |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.Save |  Avg| 11ms| 12ms | 1ms | 8.918
| |  P99| 73ms| 67ms | -6ms | -8.276
| ChannelStore.SaveMember |  Avg| 26ms| 26ms | 0s | 0.000
| |  P99| 90ms| 89ms | -1ms | -1.113
| ChannelStore.SearchGroupChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.202
| ChannelStore.UpdateLastViewedAt |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 21ms| 21ms | 0s | 0.000
| ChannelStore.UpdateSidebarCategories |  Avg| 35ms| 31ms | -4ms | -11.436
| |  P99| 91ms| 50ms | -41ms | -45.055
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 7ms | 2ms | 40.082
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 13ms| 19ms | 6ms | 45.113
| CommandWebhookStore.Cleanup |  Avg| 2ms| 3ms | 1ms | 53.186
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.AttachToPost |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 22ms| 21ms | -1ms | -4.564
| FileInfoStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.Save |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 20ms| 10ms | -10ms | -50.582
| FileInfoStore.SetContent |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 39ms| 25ms | -14ms | -35.593
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 11ms| 9ms | -2ms | -17.525
| GroupStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 15ms| 10ms | -5ms | -32.692
| GroupStore.GetGroups |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| JobStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.GetAllByStatus |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 12ms | 7ms | 140.625
| JobStore.GetCountByStatusAndType |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 5ms | -3ms | -39.735
| JobStore.GetNewestJobByStatusesAndType |  Avg| 2ms| 1ms | -1ms | -64.398
| |  P99| 10ms| 8ms | -2ms | -19.417
| JobStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 10ms| 21ms | 11ms | 112.704
| JobStore.UpdateOptimistically |  Avg| 4ms| 5ms | 1ms | 22.383
| |  P99| 10ms| 18ms | 8ms | 82.368
| JobStore.UpdateStatus |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 18ms| 10ms | -8ms | -44.199
| JobStore.UpdateStatusOptimistically |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| LinkMetadataStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Save |  Avg| 2ms| 4ms | 2ms | 94.737
| |  P99| 7ms| 10ms | 3ms | 41.021
| PluginStore.Delete |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 15ms| 16ms | 1ms | 6.534
| PluginStore.List |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PluginStore.SetWithOptions |  Avg| 7ms| 8ms | 1ms | 14.014
| |  P99| 24ms| 24ms | 0s | 0.000
| PostAcknowledgementStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 17ms| 5ms | -12ms | -68.769
| PostAcknowledgementStore.GetForPosts |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| PostPersistentNotificationStore.DeleteExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -46.512
| PostPersistentNotificationStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.GetSingle |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPriorityStore.GetForPost |  Avg| 2ms| 1ms | -1ms | -63.557
| |  P99| 24ms| 5ms | -19ms | -80.085
| PostPriorityStore.GetForPosts |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.470
| PostStore.AnalyticsPostCount |  Avg| 4.015s| 3.89s | -125ms | -3.113
| |  P99| 4.975s| 4.975s | 0s | 0.000
| PostStore.Delete |  Avg| 15ms| 14ms | -1ms | -6.788
| |  P99| 25ms| 25ms | 0s | 0.000
| PostStore.Get |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 13ms | 3ms | 28.763
| PostStore.GetEtag |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 15ms| 14ms | -1ms | -6.465
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 16ms| 14ms | -2ms | -12.621
| PostStore.GetPostIdBeforeTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| PostStore.GetPostReminderMetadata |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostReminders |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| PostStore.GetPosts |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 44ms| 44ms | 0s | 0.000
| PostStore.GetPostsAfter |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostsBefore |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| PostStore.GetPostsByThread |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostsSince |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 46ms| 46ms | 0s | 0.000
| PostStore.GetSingle |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 49ms| 48ms | -1ms | -2.061
| PostStore.SearchPostsForUser |  Avg| 122ms| 118ms | -4ms | -3.272
| |  P99| 832ms| 500ms | -332ms | -39.920
| PostStore.SetPostReminder |  Avg| 8ms| 9ms | 1ms | 11.801
| |  P99| 24ms| 24ms | 0s | 0.000
| PostStore.Update |  Avg| 19ms| 19ms | 0s | 0.000
| |  P99| 45ms| 44ms | -1ms | -2.215
| PreferenceStore.DeleteCategoryAndName |  Avg| 4ms| 5ms | 1ms | 24.013
| |  P99| 24ms| 24ms | 0s | 0.000
| PreferenceStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| PreferenceStore.GetAll |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 21ms | 0s | 0.000
| PreferenceStore.Save |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 46ms| 45ms | -1ms | -2.189
| ProductNoticesStore.ClearOldNotices |  Avg| 2ms| 6ms | 4ms | 181.363
| |  P99| 5ms| 10ms | 5ms | 101.001
| ProductNoticesStore.View |  Avg| 42ms| 41ms | -1ms | -2.390
| |  P99| 164ms| 160ms | -4ms | -2.446
| ReactionStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ReactionStore.Save |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| RoleStore.ChannelHigherScopedPermissions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -45.377
| RoleStore.GetByNames |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Get |  Avg| 5ms| 4ms | -1ms | -18.392
| |  P99| 34ms| 30ms | -4ms | -11.839
| SessionStore.GetSessionsExpired |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 5ms | -2ms | -27.173
| SessionStore.Remove |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| SessionStore.Save |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| SessionStore.UpdateLastActivityAt |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| StatusStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 12ms| 13ms | 1ms | 8.244
| StatusStore.GetByIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.SaveOrUpdate |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 15ms| 17ms | 2ms | 13.421
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| StatusStore.UpdateLastActivityAt |  Avg| 5ms| 4ms | -1ms | -21.915
| |  P99| 12ms| 10ms | -2ms | -16.746
| SystemStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 16ms| 17ms | 1ms | 6.388
| TeamStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetAllPage |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 16ms| 10ms | -6ms | -37.918
| TeamStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -17.778
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 2ms| 1ms | -1ms | -66.002
| |  P99| 15ms| 10ms | -5ms | -34.435
| TeamStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -17.174
| TeamStore.GetTeamsByUserId |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 15ms| 16ms | 1ms | 6.638
| TeamStore.GetTeamsForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 11ms| 13ms | 2ms | 19.003
| TeamStore.SaveMember |  Avg| 68ms| 68ms | 0s | 0.000
| |  P99| 153ms| 143ms | -10ms | -6.553
| ThreadStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetMembershipForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 6ms | -1ms | -14.706
| ThreadStore.GetTeamsUnreadForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 16ms | -3ms | -16.116
| ThreadStore.GetThreadFollowers |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 5ms | -2ms | -27.218
| ThreadStore.GetThreadForUser |  Avg| 3ms| 2ms | -1ms | -39.631
| |  P99| 14ms| 11ms | -3ms | -21.522
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetThreadsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ThreadStore.GetTotalThreads |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.006
| ThreadStore.GetTotalUnreadMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 18ms| 13ms | -5ms | -27.996
| ThreadStore.GetTotalUnreadThreads |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 11ms| 9ms | -2ms | -18.419
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 11ms| 9ms | -2ms | -18.329
| ThreadStore.MaintainMembership |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 23ms| 22ms | -1ms | -4.441
| ThreadStore.MarkAllAsReadByChannels |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ThreadStore.MarkAllAsReadByTeam |  Avg| 2ms| 0s | -2ms | -97.474
| |  P99| 5ms| 0s | -5ms | -101.010
| ThreadStore.MarkAsRead |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ThreadStore.UpdateMembership |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| TokenStore.Cleanup |  Avg| 2ms| 3ms | 1ms | 52.223
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AutocompleteUsersInChannel |  Avg| 134ms| 135ms | 1ms | 0.749
| |  P99| 357ms| 367ms | 10ms | 2.803
| UserStore.Count |  Avg| 75ms| 63ms | -12ms | -15.920
| |  P99| 99ms| 99ms | 0s | 0.000
| UserStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 5ms | -2ms | -28.333
| UserStore.GetAllProfiles |  Avg| 9ms| 7ms | -2ms | -22.822
| |  P99| 223ms| 207ms | -16ms | -7.182
| UserStore.GetAllProfilesInChannel |  Avg| 290ms| 286ms | -4ms | -1.380
| |  P99| 934ms| 943ms | 9ms | 0.963
| UserStore.GetByUsername |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 11ms | 6ms | 121.212
| UserStore.GetForLogin |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 18ms| 15ms | -3ms | -16.933
| UserStore.GetMany |  Avg| 1ms| 4ms | 3ms | 319.569
| |  P99| 5ms| 24ms | 19ms | 383.838
| UserStore.GetProfileByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 12ms| 10ms | -2ms | -16.828
| UserStore.GetProfilesByUsernames |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetUnreadCount |  Avg| 16ms| 12ms | -4ms | -25.560
| |  P99| 648ms| 555ms | -93ms | -14.353
| UserStore.IsEmpty |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.Save |  Avg| 69ms| 69ms | 0s | 0.000
| |  P99| 167ms| 153ms | -14ms | -8.401
| UserStore.Search |  Avg| 28ms| 30ms | 2ms | 7.098
| |  P99| 243ms| 243ms | 0s | 0.000
| UserStore.Update |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 21ms| 22ms | 1ms | 4.664
| UserStore.UpdateFailedPasswordAttempts |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 25ms| 24ms | -1ms | -4.068
| UserStore.UpdateUpdateAt |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 22ms| 21ms | -1ms | -4.545
| UserTermsOfServiceStore.GetByUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 13ms| 12ms | -1ms | -7.445
| WebhookStore.GetOutgoingByTeam |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 202ms| 199ms | -3ms | -1.486
| | P99| 474ms| 478ms | 4ms | 0.844
| addTeamMember | Avg| 880ms| 869ms | -11ms | -1.251
| | P99| 2.437s| 2.441s | 4ms | 0.164
| autocompleteChannelsForTeamForSearch | Avg| 311ms| 307ms | -4ms | -1.286
| | P99| 2.426s| 3.06s | 634ms | 26.129
| autocompleteUsers | Avg| 103ms| 104ms | 1ms | 0.970
| | P99| 307ms| 319ms | 12ms | 3.906
| createChannel | Avg| 25ms| 25ms | 0s | 0.000
| | P99| 50ms| 49ms | -1ms | -2.018
| createDirectChannel | Avg| 205ms| 206ms | 1ms | 0.488
| | P99| 491ms| 490ms | -1ms | -0.204
| createGroupChannel | Avg| 301ms| 278ms | -23ms | -7.635
| | P99| 497ms| 496ms | -1ms | -0.201
| createPost | Avg| 308ms| 345ms | 37ms | 12.006
| | P99| 1.523s| 2s | 477ms | 31.323
| createUser | Avg| 97ms| 96ms | -1ms | -1.035
| | P99| 244ms| 244ms | 0s | 0.000
| deletePost | Avg| 19ms| 18ms | -1ms | -5.321
| | P99| 47ms| 25ms | -22ms | -47.057
| followThreadByUser | Avg| 10ms| 11ms | 1ms | 9.614
| | P99| 25ms| 25ms | 0s | 0.000
| getAllTeams | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 19ms| 16ms | -3ms | -15.425
| getCategoriesForTeamForUser | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 31ms| 27ms | -4ms | -12.889
| getChannel | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 10ms| 7ms | -3ms | -29.125
| getChannelMember | Avg| 6ms| 5ms | -1ms | -17.322
| | P99| 40ms| 38ms | -2ms | -5.011
| getChannelMembersForTeamForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 10ms| 9ms | -1ms | -10.080
| getChannelStats | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 190ms| 189ms | -1ms | -0.526
| getChannelUnread | Avg| 1ms| 2ms | 1ms | 85.347
| | P99| 5ms| 9ms | 4ms | 80.808
| getChannelsForTeamForUser | Avg| 3ms| 2ms | -1ms | -38.905
| | P99| 17ms| 15ms | -2ms | -11.883
| getChannelsForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 8ms| 5ms | -3ms | -38.961
| getClientConfig | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 38ms| 38ms | 0s | 0.000
| getFilePreview | Avg| 39ms| 38ms | -1ms | -2.569
| | P99| 202ms| 195ms | -7ms | -3.468
| getFileThumbnail | Avg| 29ms| 29ms | 0s | 0.000
| | P99| 96ms| 96ms | 0s | 0.000
| getPostThread | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 21ms| 22ms | 1ms | 4.704
| getPostsForChannel | Avg| 16ms| 16ms | 0s | 0.000
| | P99| 130ms| 137ms | 7ms | 5.400
| getPostsForChannelAroundLastUnread | Avg| 17ms| 17ms | 0s | 0.000
| | P99| 93ms| 86ms | -7ms | -7.529
| getPreferences | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 22ms| 21ms | -1ms | -4.579
| getProfileImage | Avg| 107ms| 105ms | -2ms | -1.871
| | P99| 486ms| 488ms | 2ms | 0.411
| getPublicChannelsForTeam | Avg| 10ms| 12ms | 2ms | 19.456
| | P99| 25ms| 58ms | 33ms | 133.693
| getTeamMember | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 8ms| 7ms | -1ms | -13.245
| getTeamMembersForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 21ms| 19ms | -2ms | -9.459
| getTeamsForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 16ms| 16ms | 0s | 0.000
| getTeamsUnreadForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 24ms| 21ms | -3ms | -12.571
| getThreadsForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 10ms| 9ms | -1ms | -10.412
| getUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 23ms| 20ms | -3ms | -13.127
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 10ms| 8ms | -2ms | -19.163
| | P99| 223ms| 208ms | -15ms | -6.715
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsersByNames | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| login | Avg| 62ms| 62ms | 0s | 0.000
| | P99| 247ms| 248ms | 1ms | 0.405
| logout | Avg| 39ms| 42ms | 3ms | 7.713
| | P99| 50ms| 97ms | 47ms | 94.464
| patchPost | Avg| 255ms| 711ms | 456ms | 179.169
| | P99| 10s| 9.475s | -525ms | -5.250
| removeUserCustomStatus | Avg| 129ms| 131ms | 2ms | 1.551
| | P99| 248ms| 248ms | 0s | 0.000
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 16ms| 16ms | 0s | 0.000
| | P99| 45ms| 43ms | -2ms | -4.492
| searchAllChannels | Avg| 46ms| 45ms | -1ms | -2.188
| | P99| 337ms| 174ms | -163ms | -48.427
| searchGroupChannels | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 8ms| 9ms | 1ms | 11.982
| searchPostsInTeam | Avg| 126ms| 121ms | -5ms | -3.954
| | P99| 874ms| 990ms | 116ms | 13.276
| searchUsers | Avg| 29ms| 31ms | 2ms | 6.886
| | P99| 243ms| 243ms | 0s | 0.000
| setPostReminder | Avg| 14ms| 15ms | 1ms | 7.362
| | P99| 25ms| 25ms | 0s | 0.000
| unfollowThreadByUser | Avg| 10ms| 11ms | 1ms | 9.744
| | P99| 25ms| 25ms | 0s | 0.000
| updateCategoriesForTeamForUser | Avg| 46ms| 46ms | 0s | 0.000
| | P99| 97ms| 217ms | 120ms | 123.711
| updatePreferences | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| updateReadStateAllThreadsByUser | Avg| 2ms| 0s | -2ms | -92.860
| | P99| 5ms| 0s | -5ms | -101.010
| updateReadStateThreadByUser | Avg| 21ms| 21ms | 0s | 0.000
| | P99| 48ms| 48ms | 0s | 0.000
| updateUserCustomStatus | Avg| 141ms| 140ms | -1ms | -0.707
| | P99| 375ms| 248ms | -127ms | -33.866
| uploadFileStream | Avg| 472ms| 455ms | -17ms | -3.598
| | P99| 1.923s| 1.481s | -442ms | -22.983
| viewChannel | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
