### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostStore.AnalyticsPostCount | avg | 1ms | 230ms | 229ms | 19785.54
| EmojiStore.GetMultipleByName | avg | 1ms | 5ms | 4ms | 417.33
| CommandWebhookStore.Cleanup | avg | 2ms | 5ms | 3ms | 195.66
| PreferenceStore.DeleteCategoryAndName | avg | 2ms | 5ms | 3ms | 180.10
| RoleStore.GetByNames | avg | 1ms | 3ms | 2ms | 155.65
| ComplianceStore.MessageExport | avg | 2ms | 5ms | 3ms | 126.13
| DraftStore.DeleteDraftsAssociatedWithPost | avg | 3ms | 6ms | 3ms | 96.15
| PostStore.SearchPostsForUser | avg | 16ms | 25ms | 9ms | 55.65
| ChannelBookmarkStore.Save | avg | 7ms | 10ms | 3ms | 40.29
| UserStore.GetProfilesInChannel | avg | 32ms | 41ms | 9ms | 27.74
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostStore.AnalyticsPostCount | p99 | 5ms | 495ms | 490ms | 9895.80
| DraftStore.DeleteDraftsAssociatedWithPost | p99 | 5ms | 47ms | 42ms | 848.48
| PreferenceStore.DeleteCategoryAndName | p99 | 5ms | 47ms | 42ms | 848.48
| RoleStore.GetByNames | p99 | 5ms | 46ms | 41ms | 828.28
| ScheduledPostStore.GetPendingScheduledPosts | p99 | 9ms | 46ms | 37ms | 404.08
| EmojiStore.GetMultipleByName | p99 | 5ms | 25ms | 20ms | 403.90
| PostStore.SearchPostsForUser | p99 | 194ms | 522ms | 328ms | 169.31
| PostAcknowledgementStore.GetForPost | p99 | 7ms | 18ms | 11ms | 156.02
| CommandWebhookStore.Cleanup | p99 | 5ms | 10ms | 5ms | 100.96
| JobStore.GetCountByStatusAndType | p99 | 21ms | 38ms | 17ms | 82.03
| PostStore.GetPostReminderMetadata | p99 | 5ms | 9ms | 4ms | 80.79
| FileInfoStore.GetByIds | p99 | 5ms | 9ms | 4ms | 74.77
| StatusStore.GetByIds | p99 | 5ms | 8ms | 3ms | 58.89
| StatusStore.SaveOrUpdate | p99 | 11ms | 17ms | 6ms | 53.09
| ChannelStore.GetPublicChannelsForTeam | p99 | 25ms | 38ms | 13ms | 52.31
| ChannelStore.GetPinnedPostCount | p99 | 5ms | 7ms | 2ms | 40.21
| FileInfoStore.Save | p99 | 10ms | 14ms | 4ms | 40.06
| ThreadStore.GetTotalUnreadThreads | p99 | 10ms | 13ms | 3ms | 30.86
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 10ms | 13ms | 3ms | 30.64
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 95ms | 122ms | 27ms | 28.48
| ChannelStore.AutocompleteInTeamForSearch | p99 | 96ms | 123ms | 27ms | 28.21
| TeamStore.GetMember | p99 | 11ms | 14ms | 3ms | 28.15
| StatusStore.Get | p99 | 9ms | 11ms | 2ms | 21.52
| PostStore.Get | p99 | 14ms | 17ms | 3ms | 20.99
| UserTermsOfServiceStore.GetByUser | p99 | 10ms | 12ms | 2ms | 19.28
| WebhookStore.GetOutgoingByTeam | p99 | 26ms | 31ms | 5ms | 19.20
| TeamStore.GetTeamsForUser | p99 | 16ms | 19ms | 3ms | 18.89
| ChannelStore.GetMember | p99 | 19ms | 22ms | 3ms | 15.42
| UserStore.GetForLogin | p99 | 13ms | 15ms | 2ms | 15.15
| PostStore.GetPosts | p99 | 15ms | 17ms | 2ms | 12.98
| JobStore.GetAllByStatus | p99 | 17ms | 19ms | 2ms | 11.75
| ChannelStore.CreateDirectChannel | p99 | 43ms | 48ms | 5ms | 11.71
| UserStore.UpdateFailedPasswordAttempts | p99 | 22ms | 24ms | 2ms | 8.99
| UserStore.Search | p99 | 50ms | 54ms | 4ms | 8.01
| UserStore.AutocompleteUsersInChannel | p99 | 172ms | 181ms | 9ms | 5.22
| PreferenceStore.Save | p99 | 40ms | 42ms | 2ms | 5.04
| UserStore.GetProfilesInChannel | p99 | 242ms | 245ms | 3ms | 1.24
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| UserStore.GetProfileByGroupChannelIdsForUser | avg | 3ms | 0s | -3ms | -101.84
| ChannelMemberHistoryStore.GetUsersInChannelDuring | avg | 55ms | 0s | -55ms | -99.40
| ChannelBookmarkStore.Delete | avg | 4ms | 0s | -4ms | -95.00
| ChannelStore.AnalyticsTypeCount | avg | 7ms | 1ms | -6ms | -87.42
| ChannelStore.GetTeamChannels | avg | 27ms | 9ms | -18ms | -65.55
| TeamStore.GetTotalMemberCount | avg | 23ms | 18ms | -5ms | -21.41
| ChannelStore.UpdateSidebarCategories | avg | 41ms | 33ms | -8ms | -19.41
| ChannelStore.AutocompleteInTeamForSearch | avg | 31ms | 29ms | -2ms | -6.43
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| GroupStore.GetGroupsAssociatedToChannelsByTeam | p99 | 5ms | 0s | -5ms | -101.01
| ChannelBookmarkStore.Get | p99 | 5ms | 0s | -5ms | -101.01
| RetentionPolicyStore.GetAll | p99 | 5ms | 0s | -5ms | -101.01
| ChannelBookmarkStore.Delete | p99 | 5ms | 0s | -5ms | -101.01
| RetentionPolicyStore.GetCount | p99 | 5ms | 0s | -5ms | -101.01
| ProductNoticesStore.GetViews | p99 | 5ms | 0s | -5ms | -101.01
| UserStore.GetProfileByGroupChannelIdsForUser | p99 | 5ms | 0s | -5ms | -100.93
| ChannelMemberHistoryStore.GetUsersInChannelDuring | p99 | 99ms | 0s | -99ms | -99.51
| ChannelStore.AnalyticsTypeCount | p99 | 25ms | 5ms | -20ms | -80.90
| PluginStore.List | p99 | 20ms | 5ms | -15ms | -76.53
| ChannelStore.GetTeamChannels | p99 | 98ms | 24ms | -74ms | -75.51
| JobStore.Save | p99 | 19ms | 8ms | -11ms | -59.30
| PostStore.GetPostReminders | p99 | 22ms | 10ms | -12ms | -53.45
| DraftStore.GetDraftsForUser | p99 | 14ms | 7ms | -7ms | -50.72
| TeamStore.GetTotalMemberCount | p99 | 49ms | 25ms | -24ms | -48.98
| ChannelStore.UpdateSidebarCategories | p99 | 97ms | 50ms | -47ms | -48.58
| PostPersistentNotificationStore.Get | p99 | 9ms | 5ms | -4ms | -46.51
| ThreadStore.MarkAllAsReadByChannels | p99 | 9ms | 5ms | -4ms | -42.40
| UserStore.GetByUsername | p99 | 8ms | 5ms | -3ms | -39.30
| ChannelStore.GetChannelsByUser | p99 | 8ms | 5ms | -3ms | -39.28
| PostStore.GetPostsAfter | p99 | 8ms | 5ms | -3ms | -35.93
| ReactionStore.GetForPost | p99 | 17ms | 11ms | -6ms | -35.76
| ThreadStore.Get | p99 | 7ms | 5ms | -2ms | -26.67
| TeamStore.SaveMember | p99 | 67ms | 51ms | -16ms | -23.94
| ThreadStore.GetMembershipForUser | p99 | 9ms | 7ms | -2ms | -22.24
| UserStore.GetAllProfiles | p99 | 14ms | 11ms | -3ms | -21.31
| PostStore.GetPostIdAfterTime | p99 | 11ms | 9ms | -2ms | -17.42
| FileInfoStore.AttachToPost | p99 | 18ms | 16ms | -2ms | -11.30
| ChannelStore.SearchGroupChannels | p99 | 21ms | 19ms | -2ms | -9.66
| UserStore.Update | p99 | 22ms | 20ms | -2ms | -9.24
| ChannelStore.CreateInitialSidebarCategories | p99 | 55ms | 50ms | -5ms | -9.01
| ProductNoticesStore.View | p99 | 97ms | 95ms | -2ms | -2.06
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| searchPostsInTeam | avg | 22ms | 30ms | 8ms | 36.12
| logout | avg | 22ms | 24ms | 2ms | 8.98
| createGroupChannel | avg | 246ms | 253ms | 7ms | 2.84
| createPost | avg | 170ms | 174ms | 4ms | 2.36
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| searchPostsInTeam | p99 | 236ms | 522ms | 286ms | 121.00
| getChannel | p99 | 9ms | 17ms | 8ms | 89.68
| getTeamMember | p99 | 7ms | 12ms | 5ms | 74.20
| getPublicChannelsForTeam | p99 | 25ms | 38ms | 13ms | 52.31
| autocompleteChannelsForTeamForSearch | p99 | 96ms | 123ms | 27ms | 28.21
| updateReadStateThreadByUser | p99 | 57ms | 71ms | 14ms | 24.59
| upsertDraft | p99 | 12ms | 15ms | 3ms | 24.46
| patchPost | p99 | 44ms | 52ms | 8ms | 18.16
| searchUsers | p99 | 50ms | 59ms | 9ms | 17.94
| getClientConfig | p99 | 28ms | 32ms | 4ms | 14.07
| autocompleteUsers | p99 | 147ms | 166ms | 19ms | 12.91
| updatePreferences | p99 | 20ms | 22ms | 2ms | 9.88
| saveReaction | p99 | 25ms | 27ms | 2ms | 8.08
| getPostsForChannelAroundLastUnread | p99 | 50ms | 53ms | 3ms | 6.05
| getChannelMember | p99 | 41ms | 43ms | 2ms | 4.88
| createPost | p99 | 743ms | 763ms | 20ms | 2.69
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| updateChannelBookmark | avg | 5ms | 0s | -5ms | -110.93
| updateCategoryForTeamForUser | avg | 66ms | 0s | -66ms | -99.63
| createChannelBookmark | avg | 26ms | 15ms | -11ms | -42.97
| updateCategoriesForTeamForUser | avg | 54ms | 47ms | -7ms | -13.00
| createChannel | avg | 217ms | 192ms | -25ms | -11.50
| deletePost | avg | 18ms | 16ms | -2ms | -11.13
| getProfileImage | avg | 76ms | 69ms | -7ms | -9.21
| autocompleteChannelsForTeamForSearch | avg | 31ms | 29ms | -2ms | -6.41
| createDirectChannel | avg | 161ms | 156ms | -5ms | -3.10
| uploadFileStream | avg | 348ms | 339ms | -9ms | -2.59
| createUser | avg | 118ms | 115ms | -3ms | -2.55
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| updateChannelBookmark | p99 | 25ms | 0s | -25ms | -101.84
| getUserByUsername | p99 | 5ms | 0s | -5ms | -100.93
| updateCategoryForTeamForUser | p99 | 100ms | 0s | -100ms | -100.50
| unfollowThreadByUser | p99 | 79ms | 24ms | -55ms | -69.63
| followThreadByUser | p99 | 25ms | 10ms | -15ms | -61.10
| updateCategoriesForTeamForUser | p99 | 214ms | 99ms | -115ms | -53.67
| getDrafts | p99 | 14ms | 7ms | -7ms | -50.66
| createChannelBookmark | p99 | 50ms | 25ms | -25ms | -50.50
| createChannel | p99 | 490ms | 249ms | -241ms | -49.18
| deletePost | p99 | 48ms | 25ms | -23ms | -48.17
| getJobsByType | p99 | 7ms | 5ms | -2ms | -27.98
| getProfileImage | p99 | 298ms | 249ms | -49ms | -16.42
| getChannelMembersForTeamForUser | p99 | 14ms | 12ms | -2ms | -14.52
| searchGroupChannels | p99 | 21ms | 19ms | -2ms | -9.48
| addTeamMember | p99 | 1.94s | 1.765s | -175ms | -9.02
| createUser | p99 | 311ms | 294ms | -17ms | -5.47
| createDirectChannel | p99 | 466ms | 458ms | -8ms | -1.72
| addChannelMember | p99 | 413ms | 408ms | -5ms | -1.21
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 21ms | 0s | 0.000
| BotStore.Get |  Avg| 2ms| 1ms | -1ms | -53.787
| |  P99| 5ms| 5ms | 0s | 0.000
| BotStore.GetAll |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelBookmarkStore.Delete |  Avg| 4ms| 0s | -4ms | -94.996
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelBookmarkStore.Get |  Avg| 1ms| 0s | -1ms | -87.793
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 6ms | 0s | 0.000
| ChannelBookmarkStore.Save |  Avg| 7ms| 10ms | 3ms | 40.294
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelMemberHistoryStore.GetUsersInChannelDuring |  Avg| 55ms| 0s | -55ms | -99.399
| |  P99| 99ms| 0s | -99ms | -99.505
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 14ms| 15ms | 1ms | 6.966
| ChannelStore.AnalyticsTypeCount |  Avg| 7ms| 1ms | -6ms | -87.425
| |  P99| 25ms| 5ms | -20ms | -80.895
| ChannelStore.Autocomplete |  Avg| 32ms| 32ms | 0s | 0.000
| |  P99| 98ms| 98ms | 0s | 0.000
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 31ms| 29ms | -2ms | -6.427
| |  P99| 96ms| 123ms | 27ms | 28.208
| ChannelStore.CreateDirectChannel |  Avg| 15ms| 16ms | 1ms | 6.504
| |  P99| 43ms| 48ms | 5ms | 11.713
| ChannelStore.CreateInitialSidebarCategories |  Avg| 17ms| 17ms | 0s | 0.000
| |  P99| 55ms| 50ms | -5ms | -9.013
| ChannelStore.CreateSidebarCategory |  Avg| 20ms| 20ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.311
| ChannelStore.GetAllChannelMembersForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 15ms| 16ms | 1ms | 6.473
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 15ms| 16ms | 1ms | 6.728
| |  P99| 95ms| 122ms | 27ms | 28.476
| ChannelStore.GetByName |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 38ms| 37ms | -1ms | -2.660
| ChannelStore.GetByNameIncludeDeleted |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannelUnread |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 10.620
| ChannelStore.GetChannelsByUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 5ms | -3ms | -39.278
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 6ms | 0s | 0.000
| ChannelStore.GetFileCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 7ms | 1ms | 16.690
| ChannelStore.GetGuestCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 18ms | -1ms | -5.187
| ChannelStore.GetMember |  Avg| 2ms| 3ms | 1ms | 40.444
| |  P99| 19ms| 22ms | 3ms | 15.419
| ChannelStore.GetMemberCount |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 46ms| 46ms | 0s | 0.000
| ChannelStore.GetMemberForPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 14ms| 15ms | 1ms | 7.334
| ChannelStore.GetMemberLastViewedAt |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 10.945
| ChannelStore.GetMembers |  Avg| 3ms| 2ms | -1ms | -36.656
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMembersForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ChannelStore.GetMembersForUserWithPagination |  Avg| 6ms| 5ms | -1ms | -17.682
| |  P99| 10ms| 10ms | 0s | 0.000
| ChannelStore.GetPinnedPostCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 7ms | 2ms | 40.211
| ChannelStore.GetPublicChannelsForTeam |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 25ms| 38ms | 13ms | 52.308
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 11ms| 12ms | 1ms | 8.709
| |  P99| 42ms| 42ms | 0s | 0.000
| ChannelStore.GetSidebarCategory |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 25ms| 24ms | -1ms | -4.062
| ChannelStore.GetTeamChannels |  Avg| 27ms| 9ms | -18ms | -65.546
| |  P99| 98ms| 24ms | -74ms | -75.510
| ChannelStore.IncrementMentionCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 14ms| 14ms | 0s | 0.000
| ChannelStore.IsReadOnlyChannel |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 6ms | 0s | 0.000
| ChannelStore.Save |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ChannelStore.SaveMember |  Avg| 23ms| 23ms | 0s | 0.000
| |  P99| 82ms| 83ms | 1ms | 1.214
| ChannelStore.SearchGroupChannels |  Avg| 3ms| 2ms | -1ms | -39.556
| |  P99| 21ms| 19ms | -2ms | -9.658
| ChannelStore.UpdateLastViewedAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ChannelStore.UpdateSidebarCategories |  Avg| 41ms| 33ms | -8ms | -19.414
| |  P99| 97ms| 50ms | -47ms | -48.576
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 6ms| 7ms | 1ms | 18.015
| CommandWebhookStore.Cleanup |  Avg| 2ms| 5ms | 3ms | 195.659
| |  P99| 5ms| 10ms | 5ms | 100.956
| ComplianceStore.MessageExport |  Avg| 2ms| 5ms | 3ms | 126.129
| |  P99| 9ms| 10ms | 1ms | 11.429
| DraftStore.Delete |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 3ms| 6ms | 3ms | 96.150
| |  P99| 5ms| 47ms | 42ms | 848.485
| DraftStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| DraftStore.GetDraftsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 14ms| 7ms | -7ms | -50.723
| DraftStore.Upsert |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| EmojiStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 6ms | 1ms | 19.002
| EmojiStore.GetMultipleByName |  Avg| 1ms| 5ms | 4ms | 417.331
| |  P99| 5ms| 25ms | 20ms | 403.900
| FileInfoStore.AttachToPost |  Avg| 6ms| 5ms | -1ms | -18.083
| |  P99| 18ms| 16ms | -2ms | -11.305
| FileInfoStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.GetByIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 74.774
| FileInfoStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 14ms | 4ms | 40.062
| FileInfoStore.SetContent |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 15ms| 16ms | 1ms | 6.756
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.577
| GroupStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 14ms| 14ms | 0s | 0.000
| GroupStore.GetGroups |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| GroupStore.GetGroupsAssociatedToChannelsByTeam |  Avg| 1ms| 0s | -1ms | -87.789
| |  P99| 5ms| 0s | -5ms | -101.010
| JobStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.GetAllByStatus |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 17ms| 19ms | 2ms | 11.748
| JobStore.GetAllByTypePage |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.GetCountByStatusAndType |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 21ms| 38ms | 17ms | 82.027
| JobStore.GetNewestJobByStatusesAndType |  Avg| 2ms| 1ms | -1ms | -52.927
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 19ms| 8ms | -11ms | -59.299
| JobStore.UpdateOptimistically |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| JobStore.UpdateStatus |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.658
| JobStore.UpdateStatusOptimistically |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.658
| LicenseStore.GetAll |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.820
| PluginStore.Delete |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PluginStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PluginStore.List |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 20ms| 5ms | -15ms | -76.531
| PluginStore.SetWithOptions |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 21ms| 22ms | 1ms | 4.715
| PostAcknowledgementStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 18ms | 11ms | 156.020
| PostAcknowledgementStore.GetForPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| PostPersistentNotificationStore.DeleteExpired |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -46.512
| PostPersistentNotificationStore.GetSingle |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPriorityStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -16.461
| PostPriorityStore.GetForPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.AnalyticsPostCount |  Avg| 1ms| 230ms | 229ms | 19785.539
| |  P99| 5ms| 495ms | 490ms | 9895.799
| PostStore.Delete |  Avg| 12ms| 11ms | -1ms | -8.209
| |  P99| 25ms| 25ms | 0s | 0.000
| PostStore.Get |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 14ms| 17ms | 3ms | 20.994
| PostStore.GetEtag |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 11ms| 9ms | -2ms | -17.424
| PostStore.GetPostIdBeforeTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 13.456
| PostStore.GetPostReminderMetadata |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.794
| PostStore.GetPostReminders |  Avg| 6ms| 5ms | -1ms | -16.932
| |  P99| 22ms| 10ms | -12ms | -53.452
| PostStore.GetPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 15ms| 17ms | 2ms | 12.984
| PostStore.GetPostsAfter |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 5ms | -3ms | -35.930
| PostStore.GetPostsBefore |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 11ms| 10ms | -1ms | -9.303
| PostStore.GetPostsByThread |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 20ms| 20ms | 0s | 0.000
| PostStore.GetPostsSince |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 45ms| 45ms | 0s | 0.000
| PostStore.GetSingle |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 37ms| 37ms | 0s | 0.000
| PostStore.SearchPostsForUser |  Avg| 16ms| 25ms | 9ms | 55.648
| |  P99| 194ms| 522ms | 328ms | 169.314
| PostStore.SetPostReminder |  Avg| 5ms| 6ms | 1ms | 18.242
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.Update |  Avg| 11ms| 10ms | -1ms | -9.183
| |  P99| 26ms| 25ms | -1ms | -3.845
| PreferenceStore.DeleteCategoryAndName |  Avg| 2ms| 5ms | 3ms | 180.099
| |  P99| 5ms| 47ms | 42ms | 848.485
| PreferenceStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| PreferenceStore.GetAll |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 18ms| 19ms | 1ms | 5.414
| PreferenceStore.Save |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 40ms| 42ms | 2ms | 5.044
| ProductNoticesStore.GetViews |  Avg| 1ms| 0s | -1ms | -88.994
| |  P99| 5ms| 0s | -5ms | -101.010
| ProductNoticesStore.View |  Avg| 27ms| 27ms | 0s | 0.000
| |  P99| 97ms| 95ms | -2ms | -2.065
| ReactionStore.GetForPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 17ms| 11ms | -6ms | -35.764
| RetentionPolicyStore.GetAll |  Avg| 1ms| 0s | -1ms | -83.026
| |  P99| 5ms| 0s | -5ms | -101.010
| RetentionPolicyStore.GetCount |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 0s | -5ms | -101.010
| RoleStore.ChannelHigherScopedPermissions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| RoleStore.GetByNames |  Avg| 1ms| 3ms | 2ms | 155.646
| |  P99| 5ms| 46ms | 41ms | 828.283
| ScheduledPostStore.GetPendingScheduledPosts |  Avg| 2ms| 3ms | 1ms | 63.292
| |  P99| 9ms| 46ms | 37ms | 404.084
| ScheduledPostStore.GetScheduledPostsForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.UpdateOldScheduledPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| SchemeStore.GetAllPage |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Get |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 26ms| 25ms | -1ms | -3.863
| SessionStore.GetLRUSessions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| SessionStore.GetSessionsExpired |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| SessionStore.Remove |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| SessionStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 22ms| 23ms | 1ms | 4.452
| SessionStore.UpdateLastActivityAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| SharedChannelStore.HasChannel |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 11ms | 2ms | 21.519
| StatusStore.GetByIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 8ms | 3ms | 58.890
| StatusStore.SaveOrUpdate |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 11ms| 17ms | 6ms | 53.092
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.UpdateLastActivityAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| SystemStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 13ms| 13ms | 0s | 0.000
| TeamStore.AnalyticsTeamCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetActiveMemberCount |  Avg| 35ms| 35ms | 0s | 0.000
| |  P99| 50ms| 50ms | 0s | 0.000
| TeamStore.GetAllPage |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 13ms| 14ms | 1ms | 7.564
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 13ms| 13ms | 0s | 0.000
| TeamStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 11ms| 14ms | 3ms | 28.155
| TeamStore.GetTeamsByUserId |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 14ms| 13ms | -1ms | -6.987
| TeamStore.GetTeamsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 16ms| 19ms | 3ms | 18.891
| TeamStore.GetTotalMemberCount |  Avg| 23ms| 18ms | -5ms | -21.414
| |  P99| 49ms| 25ms | -24ms | -48.979
| TeamStore.SaveMember |  Avg| 21ms| 21ms | 0s | 0.000
| |  P99| 67ms| 51ms | -16ms | -23.941
| ThreadStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 5ms | -2ms | -26.669
| ThreadStore.GetMembershipForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 7ms | -2ms | -22.237
| ThreadStore.GetTeamsUnreadForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 15ms| 15ms | 0s | 0.000
| ThreadStore.GetThreadFollowers |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 14.882
| ThreadStore.GetThreadForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ThreadStore.GetThreadsForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ThreadStore.GetTotalThreads |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 11ms | 1ms | 10.439
| ThreadStore.GetTotalUnreadMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ThreadStore.GetTotalUnreadThreads |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 13ms | 3ms | 30.856
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 13ms | 3ms | 30.635
| ThreadStore.MaintainMembership |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 19ms| 18ms | -1ms | -5.232
| ThreadStore.MarkAllAsReadByChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -42.402
| ThreadStore.MarkAsRead |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ThreadStore.UpdateMembership |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 14.105
| TokenStore.Cleanup |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AnalyticsActiveCount |  Avg| 15ms| 14ms | -1ms | -6.538
| |  P99| 25ms| 25ms | 0s | 0.000
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 2ms| 1ms | -1ms | -49.406
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AutocompleteUsersInChannel |  Avg| 36ms| 36ms | 0s | 0.000
| |  P99| 172ms| 181ms | 9ms | 5.219
| UserStore.Count |  Avg| 9ms| 10ms | 1ms | 10.579
| |  P99| 23ms| 22ms | -1ms | -4.430
| UserStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.467
| UserStore.GetAllProfiles |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 14ms| 11ms | -3ms | -21.311
| UserStore.GetAllProfilesInChannel |  Avg| 150ms| 150ms | 0s | 0.000
| |  P99| 471ms| 472ms | 1ms | 0.212
| UserStore.GetByUsername |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 5ms | -3ms | -39.301
| UserStore.GetForLogin |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 13ms| 15ms | 2ms | 15.150
| UserStore.GetMany |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfileByGroupChannelIdsForUser |  Avg| 3ms| 0s | -3ms | -101.838
| |  P99| 5ms| 0s | -5ms | -100.931
| UserStore.GetProfileByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 11ms| 10ms | -1ms | -8.852
| UserStore.GetProfilesByUsernames |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| UserStore.GetProfilesInChannel |  Avg| 32ms| 41ms | 9ms | 27.737
| |  P99| 242ms| 245ms | 3ms | 1.237
| UserStore.GetProfilesNotInChannel |  Avg| 4ms| 3ms | -1ms | -28.298
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetUnreadCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 11.923
| UserStore.IsEmpty |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.Save |  Avg| 70ms| 70ms | 0s | 0.000
| |  P99| 197ms| 198ms | 1ms | 0.507
| UserStore.Search |  Avg| 26ms| 26ms | 0s | 0.000
| |  P99| 50ms| 54ms | 4ms | 8.012
| UserStore.Update |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 22ms| 20ms | -2ms | -9.238
| UserStore.UpdateFailedPasswordAttempts |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 22ms| 24ms | 2ms | 8.986
| UserStore.UpdateLastLogin |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 18ms| 19ms | 1ms | 5.412
| UserStore.UpdateUpdateAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 18ms| 19ms | 1ms | 5.485
| UserTermsOfServiceStore.GetByUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 10ms| 12ms | 2ms | 19.280
| WebhookStore.GetOutgoingByTeam |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 26ms| 31ms | 5ms | 19.197
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 167ms| 166ms | -1ms | -0.597
| | P99| 413ms| 408ms | -5ms | -1.212
| addTeamMember | Avg| 576ms| 574ms | -2ms | -0.347
| | P99| 1.94s| 1.765s | -175ms | -9.019
| autocompleteChannelsForTeamForSearch | Avg| 31ms| 29ms | -2ms | -6.414
| | P99| 96ms| 123ms | 27ms | 28.208
| autocompleteUsers | Avg| 32ms| 33ms | 1ms | 3.108
| | P99| 147ms| 166ms | 19ms | 12.911
| createCategoryForTeamForUser | Avg| 22ms| 21ms | -1ms | -4.619
| | P99| 25ms| 25ms | 0s | 0.000
| createChannel | Avg| 217ms| 192ms | -25ms | -11.497
| | P99| 490ms| 249ms | -241ms | -49.184
| createChannelBookmark | Avg| 26ms| 15ms | -11ms | -42.967
| | P99| 50ms| 25ms | -25ms | -50.505
| createDirectChannel | Avg| 161ms| 156ms | -5ms | -3.097
| | P99| 466ms| 458ms | -8ms | -1.716
| createGroupChannel | Avg| 246ms| 253ms | 7ms | 2.845
| | P99| 496ms| 496ms | 0s | 0.000
| createPost | Avg| 170ms| 174ms | 4ms | 2.357
| | P99| 743ms| 763ms | 20ms | 2.692
| createUser | Avg| 118ms| 115ms | -3ms | -2.549
| | P99| 311ms| 294ms | -17ms | -5.471
| deleteDraft | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 8ms| 8ms | 0s | 0.000
| deletePost | Avg| 18ms| 16ms | -2ms | -11.130
| | P99| 48ms| 25ms | -23ms | -48.168
| followThreadByUser | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 25ms| 10ms | -15ms | -61.098
| getAllTeams | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 17ms| 17ms | 0s | 0.000
| getCategoriesForTeamForUser | Avg| 12ms| 12ms | 0s | 0.000
| | P99| 44ms| 43ms | -1ms | -2.290
| getChannel | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 9ms| 17ms | 8ms | 89.684
| getChannelMember | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 41ms| 43ms | 2ms | 4.881
| getChannelMembers | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getChannelMembersForTeamForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 14ms| 12ms | -2ms | -14.521
| getChannelStats | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| getChannelUnread | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getChannelsForTeamForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 14ms| 15ms | 1ms | 7.112
| getChannelsForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 20ms| 20ms | 0s | 0.000
| getClientConfig | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 28ms| 32ms | 4ms | 14.065
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getDrafts | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 14ms| 7ms | -7ms | -50.662
| getFilePreview | Avg| 36ms| 36ms | 0s | 0.000
| | P99| 93ms| 93ms | 0s | 0.000
| getFileThumbnail | Avg| 30ms| 30ms | 0s | 0.000
| | P99| 85ms| 84ms | -1ms | -1.182
| getJobsByType | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 7ms| 5ms | -2ms | -27.977
| getPostThread | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 23ms| 24ms | 1ms | 4.288
| getPostsForChannel | Avg| 15ms| 14ms | -1ms | -6.831
| | P99| 95ms| 94ms | -1ms | -1.055
| getPostsForChannelAroundLastUnread | Avg| 12ms| 12ms | 0s | 0.000
| | P99| 50ms| 53ms | 3ms | 6.053
| getPreferences | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 20ms| 20ms | 0s | 0.000
| getPrevTrialLicense | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getProfileImage | Avg| 76ms| 69ms | -7ms | -9.206
| | P99| 298ms| 249ms | -49ms | -16.423
| getPublicChannelsForTeam | Avg| 13ms| 13ms | 0s | 0.000
| | P99| 25ms| 38ms | 13ms | 52.308
| getRolesByNames | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getTeamMember | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 7ms| 12ms | 5ms | 74.195
| getTeamMembersForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 22ms| 23ms | 1ms | 4.589
| getTeamStats | Avg| 35ms| 35ms | 0s | 0.000
| | P99| 50ms| 50ms | 0s | 0.000
| getTeamsForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 15ms| 14ms | -1ms | -6.799
| getTeamsUnreadForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 21ms| 21ms | 0s | 0.000
| getThreadsForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 14ms| 15ms | 1ms | 7.016
| getUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 20ms| 21ms | 1ms | 5.066
| getUserByUsername | Avg| 1ms| 0s | -1ms | -68.211
| | P99| 5ms| 0s | -5ms | -100.931
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 21ms| 21ms | 0s | 0.000
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsersByNames | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 8ms| 8ms | 0s | 0.000
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| listChannelBookmarksForChannel | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 7ms| 7ms | 0s | 0.000
| login | Avg| 55ms| 55ms | 0s | 0.000
| | P99| 241ms| 242ms | 1ms | 0.415
| logout | Avg| 22ms| 24ms | 2ms | 8.978
| | P99| 48ms| 49ms | 1ms | 2.073
| patchPost | Avg| 19ms| 19ms | 0s | 0.000
| | P99| 44ms| 52ms | 8ms | 18.156
| removeUserCustomStatus | Avg| 115ms| 115ms | 0s | 0.000
| | P99| 248ms| 248ms | 0s | 0.000
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 25ms| 27ms | 2ms | 8.075
| searchAllChannels | Avg| 32ms| 32ms | 0s | 0.000
| | P99| 98ms| 98ms | 0s | 0.000
| searchGroupChannels | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 21ms| 19ms | -2ms | -9.476
| searchPostsInTeam | Avg| 22ms| 30ms | 8ms | 36.123
| | P99| 236ms| 522ms | 286ms | 121.002
| searchUsers | Avg| 27ms| 27ms | 0s | 0.000
| | P99| 50ms| 59ms | 9ms | 17.945
| setPostReminder | Avg| 14ms| 14ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 11ms| 10ms | -1ms | -9.017
| | P99| 79ms| 24ms | -55ms | -69.625
| updateCategoriesForTeamForUser | Avg| 54ms| 47ms | -7ms | -12.996
| | P99| 214ms| 99ms | -115ms | -53.671
| updateCategoryForTeamForUser | Avg| 66ms| 0s | -66ms | -99.632
| | P99| 100ms| 0s | -100ms | -100.503
| updateChannelBookmark | Avg| 5ms| 0s | -5ms | -110.927
| | P99| 25ms| 0s | -25ms | -101.839
| updatePreferences | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 20ms| 22ms | 2ms | 9.881
| updateReadStateThreadByUser | Avg| 29ms| 29ms | 0s | 0.000
| | P99| 57ms| 71ms | 14ms | 24.592
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 348ms| 339ms | -9ms | -2.589
| | P99| 973ms| 964ms | -9ms | -0.925
| upsertDraft | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 12ms| 15ms | 3ms | 24.462
| viewChannel | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 27ms| 28ms | 1ms | 3.671
