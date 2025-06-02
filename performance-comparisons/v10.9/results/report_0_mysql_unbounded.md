### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| CommandWebhookStore.Cleanup | avg | 0s | 3ms | 3ms | 761.71
| TokenStore.Cleanup | avg | 0s | 2ms | 2ms | 556.18
| ThreadStore.MarkAllAsReadByTeam | avg | 1ms | 3ms | 2ms | 155.86
| StatusStore.SaveOrUpdate | avg | 4ms | 7ms | 3ms | 70.52
| PostStore.SearchPostsForUser | avg | 35ms | 49ms | 14ms | 39.56
| PostStore.Delete | avg | 6ms | 8ms | 2ms | 31.63
| ChannelStore.GetPublicChannelsForTeam | avg | 9ms | 11ms | 2ms | 21.54
| PostStore.AnalyticsPostCount | avg | 614ms | 663ms | 49ms | 7.97
| UserStore.Count | avg | 67ms | 69ms | 2ms | 2.97
| UserStore.AutocompleteUsersInChannel | avg | 144ms | 147ms | 3ms | 2.09
| ChannelStore.AutocompleteInTeamForSearch | avg | 155ms | 157ms | 2ms | 1.29
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| RoleStore.ChannelHigherScopedPermissions | p99 | 5ms | 18ms | 13ms | 262.57
| PostStore.Update | p99 | 25ms | 78ms | 53ms | 213.69
| StatusStore.SaveOrUpdate | p99 | 72ms | 186ms | 114ms | 158.96
| UserStore.Count | p99 | 99ms | 226ms | 127ms | 127.81
| PostStore.Delete | p99 | 10ms | 22ms | 12ms | 120.59
| ChannelStore.CreateDirectChannel | p99 | 35ms | 74ms | 39ms | 111.17
| TokenStore.Cleanup | p99 | 5ms | 10ms | 5ms | 101.01
| CommandWebhookStore.Cleanup | p99 | 5ms | 10ms | 5ms | 101.01
| PluginStore.List | p99 | 9ms | 17ms | 8ms | 87.43
| BotStore.Get | p99 | 5ms | 9ms | 4ms | 80.81
| PostStore.SearchPostsForUser | p99 | 244ms | 418ms | 174ms | 71.43
| RoleStore.GetByNames | p99 | 5ms | 8ms | 3ms | 60.61
| ChannelStore.GetPinnedPostCount | p99 | 5ms | 8ms | 3ms | 60.10
| DraftStore.Delete | p99 | 5ms | 8ms | 3ms | 59.91
| ThreadStore.GetThreadFollowers | p99 | 9ms | 14ms | 5ms | 56.45
| PostAcknowledgementStore.GetForPost | p99 | 10ms | 15ms | 5ms | 50.17
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 62ms | 88ms | 26ms | 41.86
| EmojiStore.GetByName | p99 | 5ms | 7ms | 2ms | 40.04
| ChannelStore.GetMember | p99 | 5ms | 7ms | 2ms | 40.01
| PostStore.GetPostsByThread | p99 | 5ms | 7ms | 2ms | 40.00
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 6ms | 8ms | 2ms | 32.47
| ChannelStore.GetGuestCount | p99 | 9ms | 12ms | 3ms | 32.06
| PostStore.GetEtag | p99 | 10ms | 13ms | 3ms | 30.06
| StatusStore.Get | p99 | 7ms | 9ms | 2ms | 27.71
| UserTermsOfServiceStore.GetByUser | p99 | 7ms | 9ms | 2ms | 27.63
| ChannelStore.GetChannelsByUser | p99 | 7ms | 9ms | 2ms | 27.42
| StatusStore.GetByIds | p99 | 7ms | 9ms | 2ms | 27.11
| PreferenceStore.Save | p99 | 18ms | 22ms | 4ms | 22.47
| UserStore.AutocompleteUsersInChannel | p99 | 278ms | 339ms | 61ms | 21.93
| UserStore.UpdateFailedPasswordAttempts | p99 | 9ms | 11ms | 2ms | 21.40
| SessionStore.Get | p99 | 16ms | 19ms | 3ms | 18.44
| PostStore.Get | p99 | 12ms | 14ms | 2ms | 17.10
| ChannelStore.GetByName | p99 | 24ms | 28ms | 4ms | 16.76
| SessionStore.Save | p99 | 13ms | 15ms | 2ms | 15.59
| ChannelStore.UpdateSidebarCategories | p99 | 40ms | 46ms | 6ms | 15.09
| ChannelStore.GetAllChannelMembersForUser | p99 | 16ms | 18ms | 2ms | 12.53
| ChannelStore.CreateInitialSidebarCategories | p99 | 24ms | 27ms | 3ms | 12.31
| ChannelStore.SaveMember | p99 | 49ms | 54ms | 5ms | 10.17
| WebhookStore.GetOutgoingByTeam | p99 | 30ms | 33ms | 3ms | 9.87
| ProductNoticesStore.View | p99 | 88ms | 90ms | 2ms | 2.28
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostPersistentNotificationStore.UpdateLastActivity | avg | 2ms | 0s | -2ms | -120.07
| TeamStore.GetMany | avg | 2ms | 0s | -2ms | -111.32
| ChannelStore.GetChannelsByIds | avg | 2ms | 0s | -2ms | -108.65
| PostStore.GetPostsByIds | avg | 2ms | 0s | -2ms | -100.01
| ChannelBookmarkStore.Save | avg | 8ms | 5ms | -3ms | -37.28
| ChannelStore.UpdateSidebarCategories | avg | 13ms | 10ms | -3ms | -22.73
| DraftStore.DeleteDraftsAssociatedWithPost | avg | 16ms | 13ms | -3ms | -18.75
| TeamStore.GetTotalMemberCount | avg | 87ms | 83ms | -4ms | -4.61
| TeamStore.GetActiveMemberCount | avg | 112ms | 109ms | -3ms | -2.68
| ChannelStore.Autocomplete | avg | 966ms | 954ms | -12ms | -1.24
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| TeamStore.GetMany | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.GetChannelsByIds | p99 | 5ms | 0s | -5ms | -101.01
| PostPersistentNotificationStore.UpdateLastActivity | p99 | 5ms | 0s | -5ms | -101.01
| PostStore.GetPostsByIds | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.GetTeamChannels | p99 | 228ms | 50ms | -178ms | -78.24
| ChannelBookmarkStore.Get | p99 | 23ms | 5ms | -18ms | -77.58
| ScheduledPostStore.CreateScheduledPost | p99 | 19ms | 5ms | -14ms | -73.11
| TeamStore.GetTotalMemberCount | p99 | 228ms | 100ms | -128ms | -56.26
| UserStore.GetByUsername | p99 | 10ms | 5ms | -5ms | -51.81
| ChannelBookmarkStore.Save | p99 | 47ms | 24ms | -23ms | -49.46
| UserStore.GetProfilesNotInChannel | p99 | 9ms | 5ms | -4ms | -43.24
| SessionStore.GetSessionsExpired | p99 | 9ms | 5ms | -4ms | -43.01
| PostStore.GetPostReminderMetadata | p99 | 9ms | 5ms | -4ms | -42.90
| ThreadStore.Get | p99 | 8ms | 5ms | -3ms | -38.20
| ChannelStore.GetSidebarCategory | p99 | 13ms | 9ms | -4ms | -31.50
| FileInfoStore.AttachToPost | p99 | 13ms | 10ms | -3ms | -22.70
| JobStore.GetCountByStatusAndType | p99 | 18ms | 14ms | -4ms | -22.10
| ClusterDiscoveryStore.SetLastPingAt | p99 | 19ms | 16ms | -3ms | -16.04
| DraftStore.DeleteDraftsAssociatedWithPost | p99 | 48ms | 45ms | -3ms | -6.24
| ChannelStore.AutocompleteInTeamForSearch | p99 | 2.11s | 2.005s | -105ms | -4.98
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| updateReadStateAllThreadsByUser | avg | 1ms | 3ms | 2ms | 145.44
| searchPostsInTeam | avg | 41ms | 55ms | 14ms | 34.07
| getPublicChannelsForTeam | avg | 10ms | 12ms | 2ms | 19.59
| logout | avg | 21ms | 25ms | 4ms | 19.14
| deletePost | avg | 12ms | 14ms | 2ms | 16.29
| addChannelMember | avg | 142ms | 157ms | 15ms | 10.53
| getPostsForChannel | avg | 21ms | 23ms | 2ms | 9.50
| createDirectChannel | avg | 156ms | 165ms | 9ms | 5.76
| createPost | avg | 206ms | 217ms | 11ms | 5.33
| createChannel | avg | 183ms | 187ms | 4ms | 2.19
| addTeamMember | avg | 634ms | 645ms | 11ms | 1.74
| autocompleteChannelsForTeamForSearch | avg | 155ms | 157ms | 2ms | 1.29
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| patchPost | p99 | 49ms | 144ms | 95ms | 192.71
| deletePost | p99 | 25ms | 45ms | 20ms | 80.53
| searchPostsInTeam | p99 | 250ms | 445ms | 195ms | 78.10
| getUser | p99 | 9ms | 13ms | 4ms | 43.95
| updatePreferences | p99 | 10ms | 14ms | 4ms | 41.60
| getChannel | p99 | 15ms | 21ms | 6ms | 39.83
| getChannelsForUser | p99 | 7ms | 9ms | 2ms | 26.89
| addChannelMember | p99 | 301ms | 367ms | 66ms | 21.94
| autocompleteUsers | p99 | 250ms | 294ms | 44ms | 17.62
| unfollowThreadByUser | p99 | 24ms | 27ms | 3ms | 12.27
| getTeamsUnreadForUser | p99 | 17ms | 19ms | 2ms | 11.83
| logout | p99 | 44ms | 49ms | 5ms | 11.30
| getPostsForChannel | p99 | 190ms | 205ms | 15ms | 7.89
| createChannel | p99 | 463ms | 486ms | 23ms | 4.97
| createDirectChannel | p99 | 461ms | 477ms | 16ms | 3.47
| getChannelStats | p99 | 213ms | 217ms | 4ms | 1.88
| createPost | p99 | 938ms | 951ms | 13ms | 1.39
| addTeamMember | p99 | 2.279s | 2.308s | 29ms | 1.27
| removeUserCustomStatus | p99 | 247ms | 250ms | 3ms | 1.21
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| deleteChannelBookmark | avg | 20ms | 0s | -20ms | -99.91
| updateChannelBookmarkSortOrder | avg | 11ms | 0s | -11ms | -98.37
| createChannelBookmark | avg | 14ms | 11ms | -3ms | -20.79
| followThreadByUser | avg | 10ms | 8ms | -2ms | -19.86
| removeUserCustomStatus | avg | 111ms | 98ms | -13ms | -11.72
| updateCategoriesForTeamForUser | avg | 23ms | 21ms | -2ms | -8.86
| getTeamStats | avg | 112ms | 109ms | -3ms | -2.67
| createUser | avg | 117ms | 114ms | -3ms | -2.57
| createGroupChannel | avg | 227ms | 223ms | -4ms | -1.76
| searchAllChannels | avg | 966ms | 954ms | -12ms | -1.24
| uploadFileStream | avg | 346ms | 342ms | -4ms | -1.15
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| deleteChannelBookmark | p99 | 50ms | 0s | -50ms | -101.01
| updateChannelBookmarkSortOrder | p99 | 25ms | 0s | -25ms | -100.81
| followThreadByUser | p99 | 92ms | 22ms | -70ms | -76.50
| createSchedulePost | p99 | 19ms | 5ms | -14ms | -73.11
| createCategoryForTeamForUser | p99 | 25ms | 10ms | -15ms | -61.10
| createChannelBookmark | p99 | 47ms | 24ms | -23ms | -48.93
| autocompleteChannelsForTeamForSearch | p99 | 2.11s | 2.005s | -105ms | -4.98
| updateCategoriesForTeamForUser | p99 | 48ms | 46ms | -2ms | -4.17
| createUser | p99 | 377ms | 371ms | -6ms | -1.59
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 12ms| 13ms | 1ms | 8.541
| BotStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.808
| ChannelBookmarkStore.Delete |  Avg| 3ms| 4ms | 1ms | 29.251
| |  P99| 10ms| 10ms | 0s | 0.000
| ChannelBookmarkStore.Get |  Avg| 3ms| 2ms | -1ms | -30.436
| |  P99| 23ms| 5ms | -18ms | -77.585
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 6ms | 1ms | 19.041
| ChannelBookmarkStore.Save |  Avg| 8ms| 5ms | -3ms | -37.281
| |  P99| 47ms| 24ms | -23ms | -49.460
| ChannelBookmarkStore.UpdateSortOrder |  Avg| 5ms| 6ms | 1ms | 19.660
| |  P99| 10ms| 10ms | 0s | 0.000
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ChannelStore.Autocomplete |  Avg| 966ms| 954ms | -12ms | -1.243
| |  P99| 2.459s| 2.457s | -2ms | -0.081
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 155ms| 157ms | 2ms | 1.290
| |  P99| 2.11s| 2.005s | -105ms | -4.976
| ChannelStore.CreateDirectChannel |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 35ms| 74ms | 39ms | 111.166
| ChannelStore.CreateInitialSidebarCategories |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 24ms| 27ms | 3ms | 12.312
| ChannelStore.CreateSidebarCategory |  Avg| 7ms| 6ms | -1ms | -14.085
| |  P99| 10ms| 10ms | 0s | 0.000
| ChannelStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ChannelStore.GetAllChannelMembersForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 16ms| 18ms | 2ms | 12.525
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 10ms| 11ms | 1ms | 10.179
| |  P99| 62ms| 88ms | 26ms | 41.857
| ChannelStore.GetByName |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 24ms| 28ms | 4ms | 16.759
| ChannelStore.GetChannelUnread |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.549
| ChannelStore.GetChannelsByIds |  Avg| 2ms| 0s | -2ms | -108.651
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelStore.GetChannelsByUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 9ms | 2ms | 27.416
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| ChannelStore.GetFileCount |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.233
| ChannelStore.GetGuestCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 12ms | 3ms | 32.064
| ChannelStore.GetMember |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 7ms | 2ms | 40.006
| ChannelStore.GetMemberCount |  Avg| 72ms| 72ms | 0s | 0.000
| |  P99| 247ms| 247ms | 0s | 0.000
| ChannelStore.GetMemberForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ChannelStore.GetMemberLastViewedAt |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 7ms | 1ms | 16.908
| ChannelStore.GetMembers |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMembersForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.955
| ChannelStore.GetMembersForUserWithPagination |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 10.786
| ChannelStore.GetPinnedPostCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 8ms | 3ms | 60.098
| ChannelStore.GetPublicChannelsForTeam |  Avg| 9ms| 11ms | 2ms | 21.543
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 22ms| 23ms | 1ms | 4.459
| ChannelStore.GetSidebarCategory |  Avg| 3ms| 4ms | 1ms | 30.371
| |  P99| 13ms| 9ms | -4ms | -31.498
| ChannelStore.GetTeamChannels |  Avg| 29ms| 29ms | 0s | 0.000
| |  P99| 228ms| 50ms | -178ms | -78.241
| ChannelStore.IncrementMentionCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 7ms | 1ms | 17.665
| ChannelStore.IsReadOnlyChannel |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.Save |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 48ms| 48ms | 0s | 0.000
| ChannelStore.SaveMember |  Avg| 20ms| 21ms | 1ms | 4.908
| |  P99| 49ms| 54ms | 5ms | 10.169
| ChannelStore.SearchGroupChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 14.876
| ChannelStore.UpdateLastViewedAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 11.856
| ChannelStore.UpdateSidebarCategories |  Avg| 13ms| 10ms | -3ms | -22.733
| |  P99| 40ms| 46ms | 6ms | 15.095
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 3ms| 2ms | -1ms | -39.708
| |  P99| 19ms| 16ms | -3ms | -16.041
| CommandWebhookStore.Cleanup |  Avg| 0s| 3ms | 3ms | 761.713
| |  P99| 5ms| 10ms | 5ms | 101.010
| DesktopTokensStore.DeleteOlderThan |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Delete |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 8ms | 3ms | 59.908
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 16ms| 13ms | -3ms | -18.754
| |  P99| 48ms| 45ms | -3ms | -6.239
| DraftStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 13.799
| DraftStore.GetDraftsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 13.079
| DraftStore.Upsert |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| EmojiStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 7ms | 2ms | 40.040
| EmojiStore.GetMultipleByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.AttachToPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 13ms| 10ms | -3ms | -22.704
| FileInfoStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 7ms | 1ms | 15.626
| FileInfoStore.GetByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 13.382
| FileInfoStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 11.155
| FileInfoStore.SetContent |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 21ms| 20ms | -1ms | -4.789
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 8ms | 2ms | 32.471
| GroupStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.373
| GroupStore.GetGroups |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 11.288
| JobStore.GetAllByStatus |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -9.570
| JobStore.GetCountByStatusAndType |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 18ms| 14ms | -4ms | -22.099
| JobStore.GetNewestJobByStatusesAndType |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 14.423
| JobStore.Save |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.UpdateOptimistically |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.UpdateStatus |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -18.182
| JobStore.UpdateStatusOptimistically |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| LinkMetadataStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| LinkMetadataStore.Save |  Avg| 2ms| 1ms | -1ms | -50.376
| |  P99| 5ms| 5ms | 0s | 0.000
| PluginStore.Delete |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PluginStore.List |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 17ms | 8ms | 87.432
| PluginStore.SetWithOptions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.727
| PostAcknowledgementStore.GetForPost |  Avg| 3ms| 2ms | -1ms | -36.162
| |  P99| 10ms| 15ms | 5ms | 50.173
| PostAcknowledgementStore.GetForPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 22ms | 1ms | 4.754
| PostPersistentNotificationStore.DeleteExpired |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.Get |  Avg| 0s| 1ms | 1ms | 204.318
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 6ms | 1ms | 18.459
| PostPersistentNotificationStore.UpdateLastActivity |  Avg| 2ms| 0s | -2ms | -120.066
| |  P99| 5ms| 0s | -5ms | -101.010
| PostPriorityStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| PostPriorityStore.GetForPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 22ms | 1ms | 4.720
| PostStore.AnalyticsPostCount |  Avg| 614ms| 663ms | 49ms | 7.975
| |  P99| 995ms| 995ms | 0s | 0.000
| PostStore.Delete |  Avg| 6ms| 8ms | 2ms | 31.629
| |  P99| 10ms| 22ms | 12ms | 120.592
| PostStore.Get |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 12ms| 14ms | 2ms | 17.100
| PostStore.GetEtag |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 13ms | 3ms | 30.063
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdBeforeTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostReminderMetadata |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -42.896
| PostStore.GetPostReminders |  Avg| 2ms| 3ms | 1ms | 40.469
| |  P99| 9ms| 10ms | 1ms | 10.929
| PostStore.GetPosts |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 19ms| 20ms | 1ms | 5.259
| PostStore.GetPostsAfter |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| PostStore.GetPostsBefore |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 11.122
| PostStore.GetPostsByIds |  Avg| 2ms| 0s | -2ms | -100.009
| |  P99| 5ms| 0s | -5ms | -101.010
| PostStore.GetPostsByThread |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 7ms | 2ms | 40.000
| PostStore.GetPostsSince |  Avg| 8ms| 9ms | 1ms | 12.210
| |  P99| 46ms| 47ms | 1ms | 2.158
| PostStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 7ms | 1ms | 15.759
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| PostStore.SearchPostsForUser |  Avg| 35ms| 49ms | 14ms | 39.565
| |  P99| 244ms| 418ms | 174ms | 71.427
| PostStore.SetPostReminder |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Update |  Avg| 10ms| 11ms | 1ms | 9.857
| |  P99| 25ms| 78ms | 53ms | 213.691
| PreferenceStore.DeleteCategoryAndName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| PreferenceStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 10.592
| PreferenceStore.GetAll |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 10.723
| PreferenceStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 18ms| 22ms | 4ms | 22.470
| ProductNoticesStore.ClearOldNotices |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 14ms| 15ms | 1ms | 6.953
| |  P99| 88ms| 90ms | 2ms | 2.279
| ReactionStore.GetForPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| RoleStore.ChannelHigherScopedPermissions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 18ms | 13ms | 262.566
| RoleStore.GetByNames |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 8ms | 3ms | 60.606
| ScheduledPostStore.CreateScheduledPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 5ms | -14ms | -73.105
| ScheduledPostStore.GetMaxMessageSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetPendingScheduledPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetScheduledPostsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 15.241
| ScheduledPostStore.UpdateOldScheduledPosts |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 16ms| 19ms | 3ms | 18.436
| SessionStore.GetLRUSessions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 14.447
| SessionStore.GetSessionsExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -43.011
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| SessionStore.Remove |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 13ms| 15ms | 2ms | 15.589
| SessionStore.UpdateLastActivityAt |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 7ms | 1ms | 16.001
| SharedChannelStore.HasChannel |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 6ms | 1ms | 20.011
| StatusStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 9ms | 2ms | 27.707
| StatusStore.GetByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 9ms | 2ms | 27.111
| StatusStore.SaveOrUpdate |  Avg| 4ms| 7ms | 3ms | 70.524
| |  P99| 72ms| 186ms | 114ms | 158.961
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.063
| StatusStore.UpdateLastActivityAt |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 15.356
| SystemStore.GetByName |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 6ms | 0s | 0.000
| TeamStore.GetActiveMemberCount |  Avg| 112ms| 109ms | -3ms | -2.675
| |  P99| 249ms| 248ms | -1ms | -0.402
| TeamStore.GetAllPage |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.953
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.499
| TeamStore.GetMany |  Avg| 2ms| 0s | -2ms | -111.315
| |  P99| 5ms| 0s | -5ms | -101.010
| TeamStore.GetMember |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 6ms | 1ms | 20.015
| TeamStore.GetTeamsByUserId |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 13.054
| TeamStore.GetTeamsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.836
| TeamStore.GetTotalMemberCount |  Avg| 87ms| 83ms | -4ms | -4.611
| |  P99| 228ms| 100ms | -128ms | -56.263
| TeamStore.SaveMember |  Avg| 67ms| 67ms | 0s | 0.000
| |  P99| 100ms| 100ms | 0s | 0.000
| ThreadStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 5ms | -3ms | -38.200
| ThreadStore.GetMembershipForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ThreadStore.GetTeamsUnreadForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ThreadStore.GetThreadFollowers |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 14ms | 5ms | 56.446
| ThreadStore.GetThreadForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 15ms| 15ms | 0s | 0.000
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 7ms | 1ms | 17.675
| ThreadStore.GetThreadsForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.152
| ThreadStore.GetTotalThreads |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 14.919
| ThreadStore.GetTotalUnreadMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ThreadStore.GetTotalUnreadThreads |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 14.802
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 14.822
| ThreadStore.MaintainMembership |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ThreadStore.MarkAllAsReadByChannels |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.MarkAllAsReadByTeam |  Avg| 1ms| 3ms | 2ms | 155.864
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.MarkAsRead |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 7ms | 1ms | 15.416
| ThreadStore.UpdateMembership |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| TokenStore.Cleanup |  Avg| 0s| 2ms | 2ms | 556.184
| |  P99| 5ms| 10ms | 5ms | 101.010
| UserAccessTokenStore.GetByToken |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AutocompleteUsersInChannel |  Avg| 144ms| 147ms | 3ms | 2.089
| |  P99| 278ms| 339ms | 61ms | 21.927
| UserStore.Count |  Avg| 67ms| 69ms | 2ms | 2.967
| |  P99| 99ms| 226ms | 127ms | 127.809
| UserStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetAllProfiles |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 11.783
| UserStore.GetAllProfilesInChannel |  Avg| 256ms| 254ms | -2ms | -0.781
| |  P99| 497ms| 498ms | 1ms | 0.201
| UserStore.GetByUsername |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 5ms | -5ms | -51.813
| UserStore.GetForLogin |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| UserStore.GetMany |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| UserStore.GetProfileByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 13.947
| UserStore.GetProfilesByUsernames |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 14.720
| UserStore.GetProfilesInChannel |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfilesNotInChannel |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -43.243
| UserStore.GetUnreadCount |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 20ms| 21ms | 1ms | 5.044
| UserStore.IsEmpty |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.Save |  Avg| 64ms| 64ms | 0s | 0.000
| |  P99| 100ms| 100ms | 0s | 0.000
| UserStore.Search |  Avg| 34ms| 35ms | 1ms | 2.969
| |  P99| 243ms| 244ms | 1ms | 0.411
| UserStore.Update |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| UserStore.UpdateFailedPasswordAttempts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 11ms | 2ms | 21.402
| UserStore.UpdateLastLogin |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 14.297
| UserStore.UpdateUpdateAt |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| UserTermsOfServiceStore.GetByUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 9ms | 2ms | 27.632
| WebhookStore.GetOutgoingByTeam |  Avg| 4ms| 5ms | 1ms | 22.583
| |  P99| 30ms| 33ms | 3ms | 9.866
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 142ms| 157ms | 15ms | 10.527
| | P99| 301ms| 367ms | 66ms | 21.940
| addTeamMember | Avg| 634ms| 645ms | 11ms | 1.736
| | P99| 2.279s| 2.308s | 29ms | 1.272
| autocompleteChannelsForTeamForSearch | Avg| 155ms| 157ms | 2ms | 1.289
| | P99| 2.11s| 2.005s | -105ms | -4.976
| autocompleteUsers | Avg| 119ms| 120ms | 1ms | 0.844
| | P99| 250ms| 294ms | 44ms | 17.616
| createCategoryForTeamForUser | Avg| 9ms| 8ms | -1ms | -10.659
| | P99| 25ms| 10ms | -15ms | -61.100
| createChannel | Avg| 183ms| 187ms | 4ms | 2.188
| | P99| 463ms| 486ms | 23ms | 4.973
| createChannelBookmark | Avg| 14ms| 11ms | -3ms | -20.794
| | P99| 47ms| 24ms | -23ms | -48.933
| createDirectChannel | Avg| 156ms| 165ms | 9ms | 5.764
| | P99| 461ms| 477ms | 16ms | 3.470
| createGroupChannel | Avg| 227ms| 223ms | -4ms | -1.760
| | P99| 494ms| 494ms | 0s | 0.000
| createPost | Avg| 206ms| 217ms | 11ms | 5.333
| | P99| 938ms| 951ms | 13ms | 1.386
| createSchedulePost | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 19ms| 5ms | -14ms | -73.105
| createUser | Avg| 117ms| 114ms | -3ms | -2.573
| | P99| 377ms| 371ms | -6ms | -1.590
| deleteChannelBookmark | Avg| 20ms| 0s | -20ms | -99.912
| | P99| 50ms| 0s | -50ms | -101.010
| deleteDraft | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 8ms| 9ms | 1ms | 12.264
| deletePost | Avg| 12ms| 14ms | 2ms | 16.291
| | P99| 25ms| 45ms | 20ms | 80.529
| followThreadByUser | Avg| 10ms| 8ms | -2ms | -19.861
| | P99| 92ms| 22ms | -70ms | -76.502
| getAllTeams | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| getCategoriesForTeamForUser | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 24ms| 24ms | 0s | 0.000
| getChannel | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 15ms| 21ms | 6ms | 39.834
| getChannelMember | Avg| 2ms| 3ms | 1ms | 40.296
| | P99| 18ms| 19ms | 1ms | 5.702
| getChannelMembers | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getChannelMembersForTeamForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 8ms| 9ms | 1ms | 12.753
| getChannelMembersForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 9ms| 10ms | 1ms | 10.682
| getChannelStats | Avg| 7ms| 8ms | 1ms | 14.996
| | P99| 213ms| 217ms | 4ms | 1.882
| getChannelUnread | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getChannelsForTeamForUser | Avg| 2ms| 3ms | 1ms | 40.373
| | P99| 8ms| 9ms | 1ms | 12.357
| getChannelsForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 7ms| 9ms | 2ms | 26.885
| getClientConfig | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 9ms| 10ms | 1ms | 10.738
| getDrafts | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 9ms| 10ms | 1ms | 11.241
| getFilePreview | Avg| 38ms| 38ms | 0s | 0.000
| | P99| 94ms| 95ms | 1ms | 1.060
| getFileThumbnail | Avg| 32ms| 32ms | 0s | 0.000
| | P99| 88ms| 88ms | 0s | 0.000
| getPostThread | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 31ms| 30ms | -1ms | -3.211
| getPostsForChannel | Avg| 21ms| 23ms | 2ms | 9.499
| | P99| 190ms| 205ms | 15ms | 7.885
| getPostsForChannelAroundLastUnread | Avg| 16ms| 16ms | 0s | 0.000
| | P99| 48ms| 49ms | 1ms | 2.063
| getPreferences | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 11ms | 1ms | 10.519
| getProfileImage | Avg| 67ms| 66ms | -1ms | -1.482
| | P99| 248ms| 249ms | 1ms | 0.403
| getPublicChannelsForTeam | Avg| 10ms| 12ms | 2ms | 19.588
| | P99| 25ms| 25ms | 0s | 0.000
| getTeamMember | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getTeamMembersForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| getTeamScheduledPosts | Avg| 4ms| 5ms | 1ms | 22.504
| | P99| 15ms| 16ms | 1ms | 6.839
| getTeamStats | Avg| 112ms| 109ms | -3ms | -2.673
| | P99| 249ms| 248ms | -1ms | -0.402
| getTeamsForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 8ms| 9ms | 1ms | 12.878
| getTeamsUnreadForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 17ms| 19ms | 2ms | 11.828
| getThreadsForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 9ms| 10ms | 1ms | 10.853
| getUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 9ms| 13ms | 4ms | 43.951
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsersByNames | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 7ms| 8ms | 1ms | 13.580
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| listChannelBookmarksForChannel | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 6ms| 7ms | 1ms | 16.112
| login | Avg| 57ms| 56ms | -1ms | -1.743
| | P99| 225ms| 227ms | 2ms | 0.887
| logout | Avg| 21ms| 25ms | 4ms | 19.137
| | P99| 44ms| 49ms | 5ms | 11.300
| patchPost | Avg| 24ms| 25ms | 1ms | 4.235
| | P99| 49ms| 144ms | 95ms | 192.714
| removeUserCustomStatus | Avg| 111ms| 98ms | -13ms | -11.718
| | P99| 247ms| 250ms | 3ms | 1.213
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 22ms| 23ms | 1ms | 4.473
| searchAllChannels | Avg| 966ms| 954ms | -12ms | -1.242
| | P99| 2.459s| 2.457s | -2ms | -0.081
| searchGroupChannels | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 7ms| 8ms | 1ms | 14.477
| searchPostsInTeam | Avg| 41ms| 55ms | 14ms | 34.070
| | P99| 250ms| 445ms | 195ms | 78.098
| searchUsers | Avg| 35ms| 36ms | 1ms | 2.886
| | P99| 243ms| 244ms | 1ms | 0.411
| setPostReminder | Avg| 13ms| 12ms | -1ms | -7.773
| | P99| 25ms| 25ms | 0s | 0.000
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 24ms| 27ms | 3ms | 12.273
| updateCategoriesForTeamForUser | Avg| 23ms| 21ms | -2ms | -8.862
| | P99| 48ms| 46ms | -2ms | -4.171
| updateChannelBookmark | Avg| 7ms| 6ms | -1ms | -13.425
| | P99| 25ms| 25ms | 0s | 0.000
| updateChannelBookmarkSortOrder | Avg| 11ms| 0s | -11ms | -98.370
| | P99| 25ms| 0s | -25ms | -100.806
| updatePreferences | Avg| 3ms| 4ms | 1ms | 29.643
| | P99| 10ms| 14ms | 4ms | 41.597
| updateReadStateAllThreadsByUser | Avg| 1ms| 3ms | 2ms | 145.443
| | P99| 5ms| 5ms | 0s | 0.000
| updateReadStateThreadByUser | Avg| 22ms| 22ms | 0s | 0.000
| | P99| 49ms| 49ms | 0s | 0.000
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 346ms| 342ms | -4ms | -1.155
| | P99| 963ms| 964ms | 1ms | 0.104
| upsertDraft | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| viewChannel | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
