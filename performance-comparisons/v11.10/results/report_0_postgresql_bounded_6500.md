### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| SessionStore.GetSessionsExpired | avg | 1ms | 3ms | 2ms | 206.49
| ScheduledPostStore.GetPendingScheduledPosts | avg | 1ms | 3ms | 2ms | 178.71
| TeamStore.GetTotalMemberCount | avg | 18ms | 33ms | 15ms | 83.57
| ChannelStore.AnalyticsCountAll | avg | 13ms | 22ms | 9ms | 67.86
| ChannelStore.AutocompleteInTeamForSearch | avg | 32ms | 40ms | 8ms | 25.33
| UserStore.AnalyticsActiveCount | avg | 12ms | 15ms | 3ms | 24.68
| PostStore.Delete | avg | 10ms | 12ms | 2ms | 19.84
| ChannelStore.GetTeamChannels | avg | 18ms | 21ms | 3ms | 16.81
| PostStore.AnalyticsPostCount | avg | 133ms | 135ms | 2ms | 1.50
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostStore.GetPostReminders | p99 | 5ms | 22ms | 17ms | 343.43
| ScheduledPostStore.GetPendingScheduledPosts | p99 | 9ms | 22ms | 13ms | 142.08
| UserStore.GetByUsername | p99 | 7ms | 16ms | 9ms | 128.12
| JobStore.UpdateStatus | p99 | 5ms | 10ms | 5ms | 101.01
| TeamStore.GetTotalMemberCount | p99 | 25ms | 50ms | 25ms | 100.57
| ChannelStore.CreateDirectChannel | p99 | 48ms | 96ms | 48ms | 99.28
| ChannelStore.GetTeamChannels | p99 | 25ms | 48ms | 23ms | 92.56
| JobStore.UpdateOptimistically | p99 | 5ms | 9ms | 4ms | 80.81
| FileInfoStore.Save | p99 | 9ms | 16ms | 7ms | 76.85
| ChannelStore.GetChannelsByUser | p99 | 13ms | 18ms | 5ms | 38.29
| UserStore.IsEmpty | p99 | 6ms | 8ms | 2ms | 35.71
| WebhookStore.GetOutgoingByTeam | p99 | 12ms | 16ms | 4ms | 34.06
| FileInfoStore.SetContent | p99 | 23ms | 30ms | 7ms | 30.03
| SessionStore.GetLRUSessions | p99 | 11ms | 14ms | 3ms | 26.92
| UserStore.TryIncrementFailedPasswordAttempts | p99 | 15ms | 19ms | 4ms | 25.89
| UserTermsOfServiceStore.GetByUser | p99 | 13ms | 16ms | 3ms | 23.87
| TeamStore.GetTeamsByUserId | p99 | 13ms | 16ms | 3ms | 23.82
| ThreadStore.MaintainMembership | p99 | 13ms | 16ms | 3ms | 23.62
| GroupStore.GetByName | p99 | 14ms | 17ms | 3ms | 21.41
| ProductNoticesStore.View | p99 | 115ms | 139ms | 24ms | 20.83
| PropertyGroupStore.Get | p99 | 10ms | 12ms | 2ms | 19.48
| PreferenceStore.Save | p99 | 41ms | 47ms | 6ms | 14.57
| UserStore.GetAllProfiles | p99 | 14ms | 16ms | 2ms | 14.39
| SystemStore.GetByName | p99 | 14ms | 16ms | 2ms | 14.08
| SessionStore.Get | p99 | 29ms | 33ms | 4ms | 13.85
| PostStore.GetPosts | p99 | 15ms | 17ms | 2ms | 13.37
| ChannelStore.GetMemberForPost | p99 | 30ms | 34ms | 4ms | 13.21
| PostStore.Get | p99 | 15ms | 17ms | 2ms | 13.02
| ChannelStore.CreateInitialSidebarCategories | p99 | 49ms | 55ms | 6ms | 12.24
| UserStore.UpdateLastLogin | p99 | 18ms | 20ms | 2ms | 11.12
| TeamStore.SaveMember | p99 | 60ms | 65ms | 5ms | 8.31
| PostStore.Save | p99 | 34ms | 36ms | 2ms | 5.81
| UserStore.Count | p99 | 38ms | 40ms | 2ms | 5.28
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 82ms | 86ms | 4ms | 4.90
| ChannelStore.SaveMember | p99 | 86ms | 89ms | 3ms | 3.47
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ThreadStore.MarkAllAsReadByTeam | avg | 2ms | 0s | -2ms | -122.87
| PostStore.GetPostIdBeforeTime | avg | 2ms | 0s | -2ms | -121.31
| SystemStore.PermanentDeleteByName | avg | 3ms | 0s | -3ms | -112.53
| SystemStore.SaveOrUpdate | avg | 3ms | 0s | -3ms | -109.39
| RetentionPolicyStore.GetAll | avg | 14ms | 0s | -14ms | -103.59
| PreferenceStore.DeleteCategoryAndName | avg | 6ms | 1ms | -5ms | -79.55
| UserStore.GetProfilesInChannel | avg | 41ms | 9ms | -32ms | -77.82
| ChannelStore.GetMany | avg | 3ms | 1ms | -2ms | -70.73
| DraftStore.DeleteDraftsAssociatedWithPost | avg | 8ms | 3ms | -5ms | -62.31
| ChannelStore.UpdateSidebarCategories | avg | 32ms | 27ms | -5ms | -15.41
| PostStore.SearchPostsForUser | avg | 140ms | 138ms | -2ms | -1.43
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.GetByNameIncludeDeleted | p99 | 5ms | 0s | -5ms | -101.01
| SystemStore.PermanentDeleteByName | p99 | 5ms | 0s | -5ms | -101.01
| RetentionPolicyStore.GetCount | p99 | 5ms | 0s | -5ms | -101.01
| ThreadStore.MarkAllAsReadByTeam | p99 | 5ms | 0s | -5ms | -101.01
| SystemStore.SaveOrUpdate | p99 | 5ms | 0s | -5ms | -101.01
| RetentionPolicyStore.GetAll | p99 | 25ms | 0s | -25ms | -100.60
| PostStore.GetPostIdBeforeTime | p99 | 5ms | 0s | -5ms | -100.23
| UserStore.GetProfilesInChannel | p99 | 246ms | 10ms | -236ms | -96.11
| ChannelStore.AutocompleteInTeamForSearch | p99 | 665ms | 112ms | -553ms | -83.15
| PreferenceStore.DeleteCategoryAndName | p99 | 25ms | 5ms | -20ms | -81.47
| ClusterDiscoveryStore.SetLastPingAt | p99 | 28ms | 6ms | -22ms | -80.00
| ChannelStore.GetMany | p99 | 24ms | 5ms | -19ms | -79.83
| DraftStore.DeleteDraftsAssociatedWithPost | p99 | 25ms | 9ms | -16ms | -65.17
| JobStore.GetCountByStatusAndType | p99 | 14ms | 5ms | -9ms | -62.07
| ChannelStore.Save | p99 | 64ms | 24ms | -40ms | -62.02
| JobStore.Save | p99 | 17ms | 7ms | -10ms | -59.70
| ReactionStore.GetForPost | p99 | 12ms | 5ms | -7ms | -58.35
| StatusStore.UpdateExpiredDNDStatuses | p99 | 12ms | 6ms | -6ms | -52.17
| PostStore.GetPostIdAfterTime | p99 | 10ms | 5ms | -5ms | -51.60
| UserStore.Update | p99 | 20ms | 10ms | -10ms | -50.63
| ChannelBookmarkStore.Delete | p99 | 10ms | 5ms | -5ms | -50.50
| ChannelStore.GetSidebarCategory | p99 | 20ms | 10ms | -10ms | -50.25
| PostStore.GetPostReminderMetadata | p99 | 9ms | 5ms | -4ms | -42.55
| FileInfoStore.AttachToPost | p99 | 16ms | 10ms | -6ms | -36.59
| JobStore.UpdateStatusOptimistically | p99 | 7ms | 5ms | -2ms | -27.59
| StatusStore.SaveOrUpdateMany | p99 | 55ms | 41ms | -14ms | -25.69
| ThreadStore.GetThreadUnreadReplyCount | p99 | 16ms | 13ms | -3ms | -18.65
| PostStore.Update | p99 | 28ms | 25ms | -3ms | -10.91
| UserStore.AutocompleteUsersInChannel | p99 | 163ms | 147ms | -16ms | -9.80
| ChannelStore.UpdateSidebarCategories | p99 | 95ms | 89ms | -6ms | -6.28
| ChannelStore.Autocomplete | p99 | 240ms | 233ms | -7ms | -2.92
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| root | avg | 2ms | 78ms | 76ms | 4945.81
| getAnalytics | avg | 22ms | 36ms | 14ms | 64.05
| autocompleteChannelsForTeamForSearch | avg | 32ms | 40ms | 8ms | 25.28
| handleCheckCWSConnection | avg | 23ms | 28ms | 5ms | 22.03
| createCategoryForTeamForUser | avg | 14ms | 16ms | 2ms | 14.48
| logout | avg | 18ms | 20ms | 2ms | 10.82
| removeUserCustomStatus | avg | 103ms | 114ms | 11ms | 10.72
| createChannel | avg | 157ms | 168ms | 11ms | 7.02
| addTeamMember | avg | 547ms | 553ms | 6ms | 1.10
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| root | p99 | 9ms | 6.046s | 6.037s | 68214.69
| getChannel | p99 | 9ms | 24ms | 15ms | 174.42
| updateCategoriesForTeamForUser | p99 | 96ms | 218ms | 122ms | 127.74
| handleCheckCWSConnection | p99 | 25ms | 50ms | 25ms | 100.60
| getChannelsForUser | p99 | 14ms | 19ms | 5ms | 34.82
| getPostsForChannelAroundLastUnread | p99 | 50ms | 65ms | 15ms | 30.13
| getTeamsForUser | p99 | 13ms | 16ms | 3ms | 22.77
| addTeamMember | p99 | 1.553s | 1.867s | 314ms | 20.21
| getUser | p99 | 20ms | 23ms | 3ms | 14.77
| patchPost | p99 | 43ms | 49ms | 6ms | 14.07
| createPost | p99 | 498ms | 560ms | 62ms | 12.44
| getClientConfig | p99 | 34ms | 38ms | 4ms | 11.65
| getPreferences | p99 | 18ms | 20ms | 2ms | 10.82
| listCPAFields | p99 | 21ms | 23ms | 2ms | 9.32
| getChannelMember | p99 | 34ms | 37ms | 3ms | 8.83
| saveReaction | p99 | 43ms | 46ms | 3ms | 7.05
| getPostsForChannel | p99 | 85ms | 91ms | 6ms | 7.03
| getProfileImage | p99 | 440ms | 455ms | 15ms | 3.41
| createUser | p99 | 460ms | 467ms | 7ms | 1.52
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| updateReadStateAllThreadsByUser | avg | 2ms | 0s | -2ms | -116.38
| getConfig | avg | 86ms | 0s | -86ms | -100.40
| updateCategoriesForTeamForUser | avg | 43ms | 36ms | -7ms | -16.41
| addChannelMember | avg | 148ms | 139ms | -9ms | -6.08
| createGroupChannel | avg | 235ms | 226ms | -9ms | -3.84
| getProfileImage | avg | 95ms | 92ms | -3ms | -3.14
| searchPostsInTeam | avg | 145ms | 143ms | -2ms | -1.37
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| updateReadStateAllThreadsByUser | p99 | 5ms | 0s | -5ms | -101.01
| getConfig | p99 | 100ms | 0s | -100ms | -100.50
| autocompleteChannelsForTeamForSearch | p99 | 665ms | 112ms | -553ms | -83.15
| updatePreferences | p99 | 16ms | 10ms | -6ms | -38.49
| autocompleteUsers | p99 | 133ms | 113ms | -20ms | -15.06
| searchAllChannels | p99 | 240ms | 233ms | -7ms | -2.92
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 3ms| 4ms | 1ms | 29.263
| |  P99| 20ms| 20ms | 0s | 0.000
| BotStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelBookmarkStore.Delete |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 10ms| 5ms | -5ms | -50.505
| ChannelBookmarkStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelBookmarkStore.Save |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 24ms| 25ms | 1ms | 4.149
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 15ms| 16ms | 1ms | 6.601
| ChannelStore.AnalyticsCountAll |  Avg| 13ms| 22ms | 9ms | 67.863
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.Autocomplete |  Avg| 35ms| 36ms | 1ms | 2.836
| |  P99| 240ms| 233ms | -7ms | -2.919
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 32ms| 40ms | 8ms | 25.334
| |  P99| 665ms| 112ms | -553ms | -83.155
| ChannelStore.CreateDirectChannel |  Avg| 16ms| 16ms | 0s | 0.000
| |  P99| 48ms| 96ms | 48ms | 99.277
| ChannelStore.CreateInitialSidebarCategories |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 49ms| 55ms | 6ms | 12.242
| ChannelStore.CreateSidebarCategory |  Avg| 13ms| 14ms | 1ms | 7.960
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 10ms| 11ms | 1ms | 10.242
| ChannelStore.GetAllChannelMembersForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 17ms| 18ms | 1ms | 5.921
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 82ms| 86ms | 4ms | 4.902
| ChannelStore.GetBoardChannel |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetByName |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 25ms | 1ms | 4.162
| ChannelStore.GetByNameIncludeDeleted |  Avg| 1ms| 0s | -1ms | -102.172
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelStore.GetChannelUnread |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannels |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ChannelStore.GetChannelsByUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 13ms| 18ms | 5ms | 38.292
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetFileCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetGuestCount |  Avg| 1ms| 2ms | 1ms | 68.110
| |  P99| 21ms| 22ms | 1ms | 4.839
| ChannelStore.GetMany |  Avg| 3ms| 1ms | -2ms | -70.729
| |  P99| 24ms| 5ms | -19ms | -79.832
| ChannelStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 19ms | 0s | 0.000
| ChannelStore.GetMemberCount |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 43ms| 44ms | 1ms | 2.352
| ChannelStore.GetMemberForPost |  Avg| 19ms| 20ms | 1ms | 5.396
| |  P99| 30ms| 34ms | 4ms | 13.205
| ChannelStore.GetMemberLastViewedAt |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 10ms| 11ms | 1ms | 10.161
| ChannelStore.GetMembersForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ChannelStore.GetMembersForUserWithPagination |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 19ms | 0s | 0.000
| ChannelStore.GetPinnedPostCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetPublicChannelsForTeam |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 2ms| 3ms | 1ms | 40.036
| |  P99| 21ms| 22ms | 1ms | 4.768
| ChannelStore.GetSidebarCategory |  Avg| 5ms| 4ms | -1ms | -21.866
| |  P99| 20ms| 10ms | -10ms | -50.251
| ChannelStore.GetTeamChannels |  Avg| 18ms| 21ms | 3ms | 16.809
| |  P99| 25ms| 48ms | 23ms | 92.555
| ChannelStore.IncrementMentionCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 12ms| 13ms | 1ms | 8.416
| ChannelStore.Save |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 64ms| 24ms | -40ms | -62.018
| ChannelStore.SaveMember |  Avg| 22ms| 22ms | 0s | 0.000
| |  P99| 86ms| 89ms | 3ms | 3.469
| ChannelStore.SearchGroupChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ChannelStore.UpdateLastViewedAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ChannelStore.UpdateSidebarCategories |  Avg| 32ms| 27ms | -5ms | -15.405
| |  P99| 95ms| 89ms | -6ms | -6.283
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 28ms| 6ms | -22ms | -80.000
| CommandWebhookStore.Cleanup |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Delete |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 8ms| 3ms | -5ms | -62.315
| |  P99| 25ms| 9ms | -16ms | -65.173
| DraftStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.GetDraftsForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Upsert |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.680
| EmojiStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| EmojiStore.GetMultipleByName |  Avg| 0s| 1ms | 1ms | 268.462
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.AttachToPost |  Avg| 6ms| 5ms | -1ms | -17.782
| |  P99| 16ms| 10ms | -6ms | -36.586
| FileInfoStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.GetByIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.GetForPost |  Avg| 2ms| 1ms | -1ms | -64.945
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 16ms | 7ms | 76.853
| FileInfoStore.SetContent |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 23ms| 30ms | 7ms | 30.027
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| GroupStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 14ms| 17ms | 3ms | 21.407
| GroupStore.GetGroups |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| GroupStore.GetGroupsAssociatedToChannelsByTeam |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.GetAllByStatus |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| JobStore.GetAllByTypePage |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.GetCountByStatusAndType |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 14ms| 5ms | -9ms | -62.069
| JobStore.GetNewestJobByStatusesAndType |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 17ms| 7ms | -10ms | -59.701
| JobStore.UpdateOptimistically |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.808
| JobStore.UpdateStatus |  Avg| 3ms| 4ms | 1ms | 34.649
| |  P99| 5ms| 10ms | 5ms | 101.010
| JobStore.UpdateStatusOptimistically |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 7ms| 5ms | -2ms | -27.586
| LicenseStore.GetAll |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| PostAcknowledgementStore.GetForPost |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostAcknowledgementStore.GetForPosts |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.DeleteExpired |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.Get |  Avg| 1ms| 2ms | 1ms | 69.929
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.GetSingle |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPriorityStore.GetForPostWithContext |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPriorityStore.GetForPosts |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 6ms | 1ms | 20.019
| PostStore.AnalyticsPostCount |  Avg| 133ms| 135ms | 2ms | 1.501
| |  P99| 495ms| 495ms | 0s | 0.000
| PostStore.AnalyticsPostCountByTeam |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Delete |  Avg| 10ms| 12ms | 2ms | 19.841
| |  P99| 25ms| 25ms | 0s | 0.000
| PostStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 15ms| 17ms | 2ms | 13.024
| PostStore.GetEtag |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 5ms | -5ms | -51.599
| PostStore.GetPostIdBeforeTime |  Avg| 2ms| 0s | -2ms | -121.313
| |  P99| 5ms| 0s | -5ms | -100.229
| PostStore.GetPostReminderMetadata |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -42.548
| PostStore.GetPostReminders |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 22ms | 17ms | 343.434
| PostStore.GetPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 15ms| 17ms | 2ms | 13.372
| PostStore.GetPostsAfter |  Avg| 1ms| 2ms | 1ms | 66.692
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostsBefore |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 14.681
| PostStore.GetPostsByThread |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 10.533
| PostStore.GetPostsSince |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 40ms| 40ms | 0s | 0.000
| PostStore.GetSingle |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 34ms| 36ms | 2ms | 5.810
| PostStore.SearchPostsForUser |  Avg| 140ms| 138ms | -2ms | -1.433
| |  P99| 974ms| 972ms | -2ms | -0.205
| PostStore.SetPostReminder |  Avg| 6ms| 5ms | -1ms | -18.098
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.Update |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 28ms| 25ms | -3ms | -10.908
| PreferenceStore.DeleteCategoryAndName |  Avg| 6ms| 1ms | -5ms | -79.549
| |  P99| 25ms| 5ms | -20ms | -81.466
| PreferenceStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PreferenceStore.GetAll |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 18ms| 19ms | 1ms | 5.512
| PreferenceStore.Save |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 41ms| 47ms | 6ms | 14.567
| ProductNoticesStore.ClearOldNotices |  Avg| 19ms| 19ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 30ms| 31ms | 1ms | 3.374
| |  P99| 115ms| 139ms | 24ms | 20.834
| PropertyFieldStore.SearchPropertyFields |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 11.561
| PropertyGroupStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 10ms| 12ms | 2ms | 19.475
| PropertyValueStore.SearchPropertyValues |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ReactionStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 12ms| 5ms | -7ms | -58.353
| RetentionPolicyStore.GetAll |  Avg| 14ms| 0s | -14ms | -103.594
| |  P99| 25ms| 0s | -25ms | -100.604
| RetentionPolicyStore.GetCount |  Avg| 1ms| 0s | -1ms | -126.285
| |  P99| 5ms| 0s | -5ms | -101.010
| RoleStore.ChannelHigherScopedPermissions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| RoleStore.GetByNames |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.CreateScheduledPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetMaxMessageSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetPendingScheduledPosts |  Avg| 1ms| 3ms | 2ms | 178.709
| |  P99| 9ms| 22ms | 13ms | 142.077
| ScheduledPostStore.GetScheduledPostsForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 10ms| 11ms | 1ms | 10.322
| ScheduledPostStore.UpdateOldScheduledPosts |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SchemeStore.GetAllPage |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 29ms| 33ms | 4ms | 13.850
| SessionStore.GetLRUSessions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 11ms| 14ms | 3ms | 26.920
| SessionStore.GetSessionsExpired |  Avg| 1ms| 3ms | 2ms | 206.487
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 6ms | 0s | 0.000
| SessionStore.Remove |  Avg| 2ms| 3ms | 1ms | 40.763
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 24ms| 25ms | 1ms | 4.225
| SessionStore.UpdateLastActivityAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| StatusStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 10.565
| StatusStore.GetByIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.SaveOrUpdate |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 22ms| 23ms | 1ms | 4.507
| StatusStore.SaveOrUpdateMany |  Avg| 9ms| 8ms | -1ms | -11.316
| |  P99| 55ms| 41ms | -14ms | -25.686
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 12ms| 6ms | -6ms | -52.174
| StatusStore.UpdateLastActivityAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 14.028
| SystemStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 14ms| 16ms | 2ms | 14.084
| SystemStore.PermanentDeleteByName |  Avg| 3ms| 0s | -3ms | -112.528
| |  P99| 5ms| 0s | -5ms | -101.010
| SystemStore.SaveOrUpdate |  Avg| 3ms| 0s | -3ms | -109.394
| |  P99| 5ms| 0s | -5ms | -101.010
| TeamStore.AnalyticsTeamCount |  Avg| 1ms| 0s | -1ms | -170.893
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetActiveMemberCount |  Avg| 34ms| 33ms | -1ms | -2.970
| |  P99| 50ms| 50ms | 0s | 0.000
| TeamStore.GetAllPage |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 15ms| 16ms | 1ms | 6.787
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 13ms| 14ms | 1ms | 7.852
| TeamStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 14ms| 14ms | 0s | 0.000
| TeamStore.GetTeamsByUserId |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 13ms| 16ms | 3ms | 23.823
| TeamStore.GetTeamsForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 15ms| 16ms | 1ms | 6.632
| TeamStore.GetTotalMemberCount |  Avg| 18ms| 33ms | 15ms | 83.569
| |  P99| 25ms| 50ms | 25ms | 100.566
| TeamStore.SaveMember |  Avg| 21ms| 21ms | 0s | 0.000
| |  P99| 60ms| 65ms | 5ms | 8.315
| TemporaryPostStore.GetExpiredPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetMembershipForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetTeamsUnreadForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 17ms| 18ms | 1ms | 5.823
| ThreadStore.GetThreadFollowers |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -16.368
| ThreadStore.GetThreadForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 15ms| 15ms | 0s | 0.000
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 16ms| 13ms | -3ms | -18.648
| ThreadStore.GetThreadsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 7ms | 1ms | 16.835
| ThreadStore.GetTotalThreads |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 11ms| 11ms | 0s | 0.000
| ThreadStore.GetTotalUnreadMentions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ThreadStore.GetTotalUnreadThreads |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 10ms| 11ms | 1ms | 10.028
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 10ms| 11ms | 1ms | 10.030
| ThreadStore.MaintainMembership |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 13ms| 16ms | 3ms | 23.617
| ThreadStore.MarkAllAsReadByChannels |  Avg| 2ms| 3ms | 1ms | 45.964
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.MarkAllAsReadByTeam |  Avg| 2ms| 0s | -2ms | -122.872
| |  P99| 5ms| 0s | -5ms | -101.010
| ThreadStore.MarkAsRead |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -16.772
| ThreadStore.UpdateMembership |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TokenStore.Cleanup |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AnalyticsActiveCount |  Avg| 12ms| 15ms | 3ms | 24.683
| |  P99| 25ms| 25ms | 0s | 0.000
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 1ms| 0s | -1ms | -165.140
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AutocompleteUsersInChannel |  Avg| 33ms| 32ms | -1ms | -3.062
| |  P99| 163ms| 147ms | -16ms | -9.796
| UserStore.Count |  Avg| 9ms| 10ms | 1ms | 10.658
| |  P99| 38ms| 40ms | 2ms | 5.282
| UserStore.Get |  Avg| 1ms| 2ms | 1ms | 69.401
| |  P99| 9ms| 10ms | 1ms | 11.134
| UserStore.GetAllProfiles |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 14ms| 16ms | 2ms | 14.394
| UserStore.GetAllProfilesInChannel |  Avg| 148ms| 149ms | 1ms | 0.676
| |  P99| 470ms| 473ms | 3ms | 0.638
| UserStore.GetByUsername |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 16ms | 9ms | 128.117
| UserStore.GetForLogin |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 15ms| 16ms | 1ms | 6.815
| UserStore.GetMany |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfileByIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| UserStore.GetProfilesByUsernames |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfilesInChannel |  Avg| 41ms| 9ms | -32ms | -77.824
| |  P99| 246ms| 10ms | -236ms | -96.113
| UserStore.GetProfilesNotInChannel |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetUnreadCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.IsEmpty |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 8ms | 2ms | 35.714
| UserStore.Save |  Avg| 119ms| 120ms | 1ms | 0.843
| |  P99| 248ms| 248ms | 0s | 0.000
| UserStore.Search |  Avg| 24ms| 24ms | 0s | 0.000
| |  P99| 49ms| 49ms | 0s | 0.000
| UserStore.TryIncrementFailedPasswordAttempts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 15ms| 19ms | 4ms | 25.889
| UserStore.Update |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 20ms| 10ms | -10ms | -50.635
| UserStore.UpdateFailedPasswordAttempts |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| UserStore.UpdateLastLogin |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 18ms| 20ms | 2ms | 11.121
| UserStore.UpdateUpdateAt |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 20ms| 21ms | 1ms | 5.099
| UserTermsOfServiceStore.GetByUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 13ms| 16ms | 3ms | 23.874
| WebhookStore.GetOutgoingByTeam |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 12ms| 16ms | 4ms | 34.061
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 148ms| 139ms | -9ms | -6.077
| | P99| 250ms| 248ms | -2ms | -0.801
| addTeamMember | Avg| 547ms| 553ms | 6ms | 1.096
| | P99| 1.553s| 1.867s | 314ms | 20.214
| autocompleteChannelsForTeamForSearch | Avg| 32ms| 40ms | 8ms | 25.284
| | P99| 665ms| 112ms | -553ms | -83.155
| autocompleteUsers | Avg| 29ms| 29ms | 0s | 0.000
| | P99| 133ms| 113ms | -20ms | -15.061
| createCategoryForTeamForUser | Avg| 14ms| 16ms | 2ms | 14.485
| | P99| 25ms| 25ms | 0s | 0.000
| createChannel | Avg| 157ms| 168ms | 11ms | 7.016
| | P99| 249ms| 248ms | -1ms | -0.402
| createChannelBookmark | Avg| 14ms| 13ms | -1ms | -7.253
| | P99| 25ms| 25ms | 0s | 0.000
| createDirectChannel | Avg| 159ms| 158ms | -1ms | -0.630
| | P99| 248ms| 248ms | 0s | 0.000
| createGroupChannel | Avg| 235ms| 226ms | -9ms | -3.835
| | P99| 495ms| 494ms | -1ms | -0.202
| createPost | Avg| 132ms| 132ms | 0s | 0.000
| | P99| 498ms| 560ms | 62ms | 12.438
| createSchedulePost | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| createUser | Avg| 174ms| 175ms | 1ms | 0.575
| | P99| 460ms| 467ms | 7ms | 1.521
| deleteDraft | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| deletePost | Avg| 15ms| 16ms | 1ms | 6.764
| | P99| 25ms| 25ms | 0s | 0.000
| followThreadByUser | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 24ms| 23ms | -1ms | -4.202
| getAgents | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getAgentsStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getAllTeams | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 18ms| 18ms | 0s | 0.000
| getAnalytics | Avg| 22ms| 36ms | 14ms | 64.050
| | P99| 49ms| 50ms | 1ms | 2.030
| getCategoriesForTeamForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 23ms| 24ms | 1ms | 4.347
| getChannel | Avg| 2ms| 3ms | 1ms | 42.925
| | P99| 9ms| 24ms | 15ms | 174.425
| getChannelMember | Avg| 4ms| 5ms | 1ms | 22.727
| | P99| 34ms| 37ms | 3ms | 8.826
| getChannelMembersForTeamForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 8ms| 9ms | 1ms | 12.915
| getChannelMembersForUser | Avg| 2ms| 3ms | 1ms | 40.486
| | P99| 19ms| 19ms | 0s | 0.000
| getChannelStats | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 24ms| 24ms | 0s | 0.000
| getChannelUnread | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getChannelsForTeamForUser | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 8ms| 8ms | 0s | 0.000
| getChannelsForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 14ms| 19ms | 5ms | 34.816
| getClientConfig | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 34ms| 38ms | 4ms | 11.646
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getConfig | Avg| 86ms| 0s | -86ms | -100.400
| | P99| 100ms| 0s | -100ms | -100.503
| getDrafts | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getFilePreview | Avg| 40ms| 41ms | 1ms | 2.481
| | P99| 96ms| 97ms | 1ms | 1.039
| getFileThumbnail | Avg| 39ms| 39ms | 0s | 0.000
| | P99| 94ms| 95ms | 1ms | 1.059
| getFilteredUsersStats | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| getJobsByType | Avg| 1ms| 0s | -1ms | -127.983
| | P99| 5ms| 5ms | 0s | 0.000
| getPostThread | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 23ms| 24ms | 1ms | 4.256
| getPostsForChannel | Avg| 11ms| 12ms | 1ms | 8.921
| | P99| 85ms| 91ms | 6ms | 7.033
| getPostsForChannelAroundLastUnread | Avg| 9ms| 10ms | 1ms | 10.694
| | P99| 50ms| 65ms | 15ms | 30.134
| getPreferences | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 18ms| 20ms | 2ms | 10.819
| getPrevTrialLicense | Avg| 0s| 1ms | 1ms | 214.281
| | P99| 5ms| 5ms | 0s | 0.000
| getProfileImage | Avg| 95ms| 92ms | -3ms | -3.142
| | P99| 440ms| 455ms | 15ms | 3.406
| getPropertyFields | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getPublicChannelsForTeam | Avg| 12ms| 12ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| getServerLimits | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| getTeamMember | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getTeamMembersForUser | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 18ms| 18ms | 0s | 0.000
| getTeamScheduledPosts | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 21ms| 22ms | 1ms | 4.748
| getTeamStats | Avg| 34ms| 33ms | -1ms | -2.962
| | P99| 50ms| 50ms | 0s | 0.000
| getTeamsForUser | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 13ms| 16ms | 3ms | 22.767
| getTeamsUnreadForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 23ms| 23ms | 0s | 0.000
| getThreadsForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 15ms| 15ms | 0s | 0.000
| getUser | Avg| 1ms| 2ms | 1ms | 66.994
| | P99| 20ms| 23ms | 3ms | 14.767
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 22ms| 23ms | 1ms | 4.619
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsersByNames | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| handleCheckCWSConnection | Avg| 23ms| 28ms | 5ms | 22.031
| | P99| 25ms| 50ms | 25ms | 100.604
| listCPAFields | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 21ms| 23ms | 2ms | 9.322
| listCPAValues | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| listChannelBookmarksForChannel | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| login | Avg| 78ms| 79ms | 1ms | 1.287
| | P99| 248ms| 250ms | 2ms | 0.805
| logout | Avg| 18ms| 20ms | 2ms | 10.820
| | P99| 25ms| 25ms | 0s | 0.000
| patchPost | Avg| 18ms| 18ms | 0s | 0.000
| | P99| 43ms| 49ms | 6ms | 14.071
| removeUserCustomStatus | Avg| 103ms| 114ms | 11ms | 10.719
| | P99| 247ms| 248ms | 1ms | 0.404
| root | Avg| 2ms| 78ms | 76ms | 4945.813
| | P99| 9ms| 6.046s | 6.037s | 68214.689
| saveReaction | Avg| 21ms| 22ms | 1ms | 4.840
| | P99| 43ms| 46ms | 3ms | 7.051
| searchAllChannels | Avg| 35ms| 36ms | 1ms | 2.821
| | P99| 240ms| 233ms | -7ms | -2.919
| searchGroupChannels | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 9ms| 9ms | 0s | 0.000
| searchPostsInTeam | Avg| 145ms| 143ms | -2ms | -1.375
| | P99| 974ms| 972ms | -2ms | -0.205
| searchUsers | Avg| 25ms| 25ms | 0s | 0.000
| | P99| 49ms| 49ms | 0s | 0.000
| setPostReminder | Avg| 16ms| 15ms | -1ms | -6.128
| | P99| 25ms| 25ms | 0s | 0.000
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 24ms| 23ms | -1ms | -4.175
| updateCategoriesForTeamForUser | Avg| 43ms| 36ms | -7ms | -16.414
| | P99| 96ms| 218ms | 122ms | 127.736
| updatePreferences | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 16ms| 10ms | -6ms | -38.493
| updateReadStateAllThreadsByUser | Avg| 2ms| 0s | -2ms | -116.376
| | P99| 5ms| 0s | -5ms | -101.010
| updateReadStateThreadByUser | Avg| 22ms| 22ms | 0s | 0.000
| | P99| 49ms| 49ms | 0s | 0.000
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 411ms| 412ms | 1ms | 0.243
| | P99| 990ms| 993ms | 3ms | 0.303
| upsertDraft | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 9ms| 10ms | 1ms | 10.606
| viewChannel | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 24ms| 25ms | 1ms | 4.095
