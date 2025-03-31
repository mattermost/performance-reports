### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostStore.AnalyticsPostCount | avg | 1ms | 136ms | 135ms | 14688.56
| StatusStore.SaveOrUpdate | avg | 4ms | 11ms | 7ms | 182.92
| ChannelStore.GetSidebarCategory | avg | 7ms | 12ms | 5ms | 66.75
| ChannelStore.CreateSidebarCategory | avg | 28ms | 30ms | 2ms | 7.26
| UserStore.GetAllProfilesInChannel | avg | 143ms | 145ms | 2ms | 1.40
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostStore.AnalyticsPostCount | p99 | 5ms | 495ms | 490ms | 9897.10
| StatusStore.SaveOrUpdate | p99 | 14ms | 180ms | 166ms | 1151.39
| ChannelStore.GetSidebarCategory | p99 | 24ms | 193ms | 169ms | 693.57
| PostStore.GetPostReminderMetadata | p99 | 5ms | 20ms | 15ms | 302.97
| PostPriorityStore.GetForPost | p99 | 5ms | 19ms | 14ms | 282.83
| JobStore.GetCountByStatusAndType | p99 | 5ms | 18ms | 13ms | 262.63
| PostStore.GetPostReminders | p99 | 10ms | 24ms | 14ms | 140.70
| JobStore.UpdateStatus | p99 | 8ms | 18ms | 10ms | 129.03
| ChannelStore.Save | p99 | 30ms | 67ms | 37ms | 121.32
| ClusterDiscoveryStore.SetLastPingAt | p99 | 9ms | 18ms | 9ms | 97.62
| ChannelStore.GetChannelUnread | p99 | 5ms | 8ms | 3ms | 60.61
| UserStore.GetByUsername | p99 | 7ms | 10ms | 3ms | 43.32
| ChannelStore.GetChannelsByUser | p99 | 5ms | 7ms | 2ms | 40.40
| ChannelStore.UpdateSidebarChannelsByPreferences | p99 | 5ms | 7ms | 2ms | 40.07
| FileInfoStore.AttachToPost | p99 | 21ms | 25ms | 4ms | 18.96
| UserStore.GetProfileByIds | p99 | 11ms | 13ms | 2ms | 18.32
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 17ms | 19ms | 2ms | 11.73
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 34ms | 37ms | 3ms | 8.87
| PreferenceStore.Save | p99 | 43ms | 45ms | 2ms | 4.65
| ChannelStore.SaveMember | p99 | 82ms | 85ms | 3ms | 3.66
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| RetentionPolicyStore.GetCount | avg | 2ms | 0s | -2ms | -116.99
| ScheduledPostStore.GetPendingScheduledPosts | avg | 5ms | 1ms | -4ms | -87.60
| UserStore.GetProfilesInChannel | avg | 62ms | 9ms | -53ms | -84.93
| ScheduledPostStore.UpdateOldScheduledPosts | avg | 4ms | 2ms | -2ms | -51.23
| ChannelStore.GetTeamChannels | avg | 16ms | 10ms | -6ms | -37.79
| ChannelStore.AutocompleteInTeamForSearch | avg | 30ms | 22ms | -8ms | -26.74
| ChannelBookmarkStore.Save | avg | 13ms | 11ms | -2ms | -15.58
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 14ms | 12ms | -2ms | -14.14
| ChannelStore.UpdateSidebarCategories | avg | 50ms | 48ms | -2ms | -3.99
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| TeamStore.GetByName | p99 | 5ms | 0s | -5ms | -101.01
| BotStore.GetAll | p99 | 5ms | 0s | -5ms | -101.01
| RetentionPolicyStore.GetAll | p99 | 5ms | 0s | -5ms | -101.01
| RetentionPolicyStore.GetCount | p99 | 5ms | 0s | -5ms | -101.01
| UserStore.GetProfilesInChannel | p99 | 247ms | 10ms | -237ms | -95.95
| ScheduledPostStore.GetPendingScheduledPosts | p99 | 48ms | 5ms | -43ms | -89.82
| ScheduledPostStore.UpdateOldScheduledPosts | p99 | 46ms | 5ms | -41ms | -89.62
| ThreadStore.MarkAllAsReadByTeam | p99 | 25ms | 5ms | -20ms | -81.47
| RoleStore.GetByNames | p99 | 23ms | 5ms | -18ms | -76.60
| RoleStore.ChannelHigherScopedPermissions | p99 | 20ms | 5ms | -15ms | -75.93
| StatusStore.UpdateExpiredDNDStatuses | p99 | 22ms | 8ms | -14ms | -62.36
| JobStore.Save | p99 | 18ms | 8ms | -10ms | -54.79
| ChannelStore.AutocompleteInTeamForSearch | p99 | 95ms | 47ms | -48ms | -50.31
| UserStore.Count | p99 | 45ms | 24ms | -21ms | -47.19
| PostPersistentNotificationStore.Get | p99 | 9ms | 5ms | -4ms | -46.51
| JobStore.UpdateOptimistically | p99 | 9ms | 5ms | -4ms | -45.45
| JobStore.UpdateStatusOptimistically | p99 | 9ms | 5ms | -4ms | -45.07
| SessionStore.Remove | p99 | 9ms | 5ms | -4ms | -42.78
| PostStore.GetPosts | p99 | 16ms | 11ms | -5ms | -31.86
| FileInfoStore.GetByIds | p99 | 7ms | 5ms | -2ms | -30.13
| ChannelStore.SearchGroupChannels | p99 | 14ms | 10ms | -4ms | -28.84
| DraftStore.GetDraftsForUser | p99 | 8ms | 6ms | -2ms | -25.86
| GroupStore.GetByName | p99 | 12ms | 9ms | -3ms | -24.13
| DraftStore.Upsert | p99 | 15ms | 12ms | -3ms | -19.43
| UserStore.GetForLogin | p99 | 11ms | 9ms | -2ms | -18.67
| WebhookStore.GetOutgoingByTeam | p99 | 29ms | 25ms | -4ms | -13.66
| ChannelStore.CreateInitialSidebarCategories | p99 | 70ms | 62ms | -8ms | -11.50
| SessionStore.Get | p99 | 27ms | 24ms | -3ms | -11.14
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 96ms | 86ms | -10ms | -10.46
| FileInfoStore.Save | p99 | 22ms | 20ms | -2ms | -9.06
| ChannelStore.GetPublicChannelsForTeam | p99 | 27ms | 25ms | -2ms | -7.53
| ChannelStore.UpdateSidebarCategories | p99 | 233ms | 218ms | -15ms | -6.44
| PostStore.SearchPostsForUser | p99 | 624ms | 588ms | -36ms | -5.77
| FileInfoStore.SetContent | p99 | 36ms | 34ms | -2ms | -5.59
| UserStore.Save | p99 | 193ms | 189ms | -4ms | -2.08
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| createChannelBookmark | avg | 17ms | 26ms | 9ms | 53.85
| updateCategoriesForTeamForUser | avg | 61ms | 73ms | 12ms | 19.75
| removeUserCustomStatus | avg | 112ms | 125ms | 13ms | 11.63
| createCategoryForTeamForUser | avg | 30ms | 33ms | 3ms | 9.98
| logout | avg | 23ms | 25ms | 2ms | 8.74
| getAnalytics | avg | 38ms | 40ms | 2ms | 5.33
| createGroupChannel | avg | 255ms | 265ms | 10ms | 3.92
| addTeamMember | avg | 546ms | 553ms | 7ms | 1.28
| createPost | avg | 166ms | 168ms | 2ms | 1.21
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| createChannelBookmark | p99 | 25ms | 98ms | 73ms | 293.76
| getFilteredUsersStats | p99 | 10ms | 25ms | 15ms | 150.72
| getTeamMember | p99 | 5ms | 12ms | 7ms | 140.07
| getChannelUnread | p99 | 5ms | 8ms | 3ms | 60.61
| unfollowThreadByUser | p99 | 25ms | 38ms | 13ms | 52.33
| getThreadsForUser | p99 | 10ms | 13ms | 3ms | 29.50
| getTeamScheduledPosts | p99 | 17ms | 19ms | 2ms | 11.49
| updateCategoriesForTeamForUser | p99 | 218ms | 240ms | 22ms | 10.07
| getCategoriesForTeamForUser | p99 | 35ms | 38ms | 3ms | 8.64
| getFileThumbnail | p99 | 87ms | 89ms | 2ms | 2.29
| createPost | p99 | 685ms | 697ms | 12ms | 1.75
| addChannelMember | p99 | 416ms | 422ms | 6ms | 1.44
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| autocompleteChannelsForTeamForSearch | avg | 30ms | 22ms | -8ms | -26.69
| createChannel | avg | 198ms | 177ms | -21ms | -10.59
| createDirectChannel | avg | 173ms | 161ms | -12ms | -6.92
| addChannelMember | avg | 164ms | 153ms | -11ms | -6.72
| getProfileImage | avg | 78ms | 76ms | -2ms | -2.56
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getChannelByNameForTeamName | p99 | 5ms | 0s | -5ms | -101.01
| getServerLimits | p99 | 5ms | 0s | -5ms | -101.01
| updateReadStateAllThreadsByUser | p99 | 25ms | 5ms | -20ms | -81.47
| autocompleteChannelsForTeamForSearch | p99 | 95ms | 47ms | -48ms | -50.31
| getPublicChannelsForTeam | p99 | 38ms | 25ms | -13ms | -34.08
| searchGroupChannels | p99 | 14ms | 10ms | -4ms | -28.84
| getDrafts | p99 | 8ms | 6ms | -2ms | -24.78
| createUser | p99 | 321ms | 271ms | -50ms | -15.56
| getPostThread | p99 | 21ms | 18ms | -3ms | -14.24
| updateReadStateThreadByUser | p99 | 73ms | 64ms | -9ms | -12.33
| upsertDraft | p99 | 17ms | 15ms | -2ms | -11.49
| searchPostsInTeam | p99 | 624ms | 588ms | -36ms | -5.77
| addTeamMember | p99 | 1.679s | 1.585s | -94ms | -5.60
| getChannelMember | p99 | 38ms | 36ms | -2ms | -5.23
| getProfileImage | p99 | 348ms | 338ms | -10ms | -2.87
| createDirectChannel | p99 | 474ms | 466ms | -8ms | -1.69
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 23ms| 22ms | -1ms | -4.413
| BotStore.Get |  Avg| 1ms| 2ms | 1ms | 86.276
| |  P99| 9ms| 10ms | 1ms | 10.929
| BotStore.GetAll |  Avg| 1ms| 0s | -1ms | -150.768
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelBookmarkStore.Delete |  Avg| 9ms| 8ms | -1ms | -10.980
| |  P99| 10ms| 10ms | 0s | 0.000
| ChannelBookmarkStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelBookmarkStore.Save |  Avg| 13ms| 11ms | -2ms | -15.584
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 17ms| 19ms | 2ms | 11.729
| ChannelStore.AnalyticsCountAll |  Avg| 19ms| 19ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.Autocomplete |  Avg| 31ms| 32ms | 1ms | 3.226
| |  P99| 98ms| 98ms | 0s | 0.000
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 30ms| 22ms | -8ms | -26.742
| |  P99| 95ms| 47ms | -48ms | -50.313
| ChannelStore.CreateDirectChannel |  Avg| 18ms| 18ms | 0s | 0.000
| |  P99| 48ms| 48ms | 0s | 0.000
| ChannelStore.CreateInitialSidebarCategories |  Avg| 21ms| 21ms | 0s | 0.000
| |  P99| 70ms| 62ms | -8ms | -11.497
| ChannelStore.CreateSidebarCategory |  Avg| 28ms| 30ms | 2ms | 7.256
| |  P99| 50ms| 50ms | 0s | 0.000
| ChannelStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ChannelStore.GetAllChannelMembersForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 14ms| 12ms | -2ms | -14.139
| |  P99| 96ms| 86ms | -10ms | -10.462
| ChannelStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.GetByNameIncludeDeleted |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannelUnread |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 8ms | 3ms | 60.606
| ChannelStore.GetChannels |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 13.346
| ChannelStore.GetChannelsByUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 7ms | 2ms | 40.404
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetFileCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetGuestCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 16ms| 17ms | 1ms | 6.354
| ChannelStore.GetMember |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 18ms| 19ms | 1ms | 5.624
| ChannelStore.GetMemberCount |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 44ms| 44ms | 0s | 0.000
| ChannelStore.GetMemberForPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.138
| ChannelStore.GetMemberLastViewedAt |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 7ms | -1ms | -12.945
| ChannelStore.GetMembers |  Avg| 2ms| 1ms | -1ms | -50.180
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMembersForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ChannelStore.GetMembersForUserWithPagination |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ChannelStore.GetPinnedPostCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -16.607
| ChannelStore.GetPublicChannelsForTeam |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 27ms| 25ms | -2ms | -7.527
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 34ms| 37ms | 3ms | 8.875
| ChannelStore.GetSidebarCategory |  Avg| 7ms| 12ms | 5ms | 66.746
| |  P99| 24ms| 193ms | 169ms | 693.571
| ChannelStore.GetTeamChannels |  Avg| 16ms| 10ms | -6ms | -37.792
| |  P99| 25ms| 24ms | -1ms | -4.024
| ChannelStore.IncrementMentionCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 16ms| 15ms | -1ms | -6.201
| ChannelStore.IsReadOnlyChannel |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.Save |  Avg| 10ms| 11ms | 1ms | 10.373
| |  P99| 30ms| 67ms | 37ms | 121.321
| ChannelStore.SaveMember |  Avg| 23ms| 23ms | 0s | 0.000
| |  P99| 82ms| 85ms | 3ms | 3.658
| ChannelStore.SearchGroupChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 14ms| 10ms | -4ms | -28.844
| ChannelStore.UpdateLastViewedAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 11ms| 12ms | 1ms | 8.737
| ChannelStore.UpdateSidebarCategories |  Avg| 50ms| 48ms | -2ms | -3.995
| |  P99| 233ms| 218ms | -15ms | -6.445
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 7ms | 2ms | 40.074
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 18ms | 9ms | 97.615
| CommandWebhookStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Delete |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.022
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| DraftStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.GetDraftsForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 6ms | -2ms | -25.862
| DraftStore.Upsert |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 15ms| 12ms | -3ms | -19.425
| EmojiStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| EmojiStore.GetMultipleByName |  Avg| 0s| 1ms | 1ms | 234.596
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.AttachToPost |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 21ms| 25ms | 4ms | 18.957
| FileInfoStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.GetByIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 5ms | -2ms | -30.132
| FileInfoStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 6ms | 1ms | 20.077
| FileInfoStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 22ms| 20ms | -2ms | -9.065
| FileInfoStore.SetContent |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 36ms| 34ms | -2ms | -5.595
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 6ms | 0s | 0.000
| GroupStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 12ms| 9ms | -3ms | -24.131
| GroupStore.GetGroups |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| GroupStore.GetGroupsAssociatedToChannelsByTeam |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.GetAllByStatus |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 13.025
| JobStore.GetAllByTypePage |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.GetCountByStatusAndType |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 18ms | 13ms | 262.626
| JobStore.GetNewestJobByStatusesAndType |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 18ms| 8ms | -10ms | -54.795
| JobStore.UpdateOptimistically |  Avg| 4ms| 3ms | -1ms | -28.459
| |  P99| 9ms| 5ms | -4ms | -45.455
| JobStore.UpdateStatus |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 8ms| 18ms | 10ms | 129.032
| JobStore.UpdateStatusOptimistically |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -45.070
| LicenseStore.GetAll |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.423
| PluginStore.Delete |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 14ms| 14ms | 0s | 0.000
| PluginStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PluginStore.List |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PluginStore.SetWithOptions |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 23ms| 24ms | 1ms | 4.298
| PostAcknowledgementStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostAcknowledgementStore.GetForPosts |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.DeleteExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -46.512
| PostPersistentNotificationStore.GetSingle |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPriorityStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 19ms | 14ms | 282.828
| PostPriorityStore.GetForPosts |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| PostStore.AnalyticsPostCount |  Avg| 1ms| 136ms | 135ms | 14688.562
| |  P99| 5ms| 495ms | 490ms | 9897.105
| PostStore.AnalyticsPostCountByTeam |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Delete |  Avg| 14ms| 15ms | 1ms | 7.335
| |  P99| 25ms| 25ms | 0s | 0.000
| PostStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 17ms| 17ms | 0s | 0.000
| PostStore.GetEtag |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 12ms| 12ms | 0s | 0.000
| PostStore.GetPostIdBeforeTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| PostStore.GetPostReminderMetadata |  Avg| 1ms| 2ms | 1ms | 74.678
| |  P99| 5ms| 20ms | 15ms | 302.970
| PostStore.GetPostReminders |  Avg| 7ms| 8ms | 1ms | 13.553
| |  P99| 10ms| 24ms | 14ms | 140.704
| PostStore.GetPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 16ms| 11ms | -5ms | -31.864
| PostStore.GetPostsAfter |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostsBefore |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.424
| PostStore.GetPostsByThread |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 19ms| 20ms | 1ms | 5.399
| PostStore.GetPostsSince |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 44ms| 44ms | 0s | 0.000
| PostStore.GetSingle |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 12ms| 13ms | 1ms | 8.042
| |  P99| 48ms| 48ms | 0s | 0.000
| PostStore.SearchPostsForUser |  Avg| 25ms| 26ms | 1ms | 3.942
| |  P99| 624ms| 588ms | -36ms | -5.767
| PostStore.SetPostReminder |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.Update |  Avg| 13ms| 14ms | 1ms | 7.444
| |  P99| 25ms| 25ms | 0s | 0.000
| PreferenceStore.DeleteCategoryAndName |  Avg| 3ms| 2ms | -1ms | -33.609
| |  P99| 9ms| 9ms | 0s | 0.000
| PreferenceStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| PreferenceStore.GetAll |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 16ms| 16ms | 0s | 0.000
| PreferenceStore.Save |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 43ms| 45ms | 2ms | 4.649
| ProductNoticesStore.GetViews |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 34ms| 35ms | 1ms | 2.908
| |  P99| 99ms| 99ms | 0s | 0.000
| ReactionStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 11.921
| RetentionPolicyStore.GetAll |  Avg| 1ms| 0s | -1ms | -91.686
| |  P99| 5ms| 0s | -5ms | -101.010
| RetentionPolicyStore.GetCount |  Avg| 2ms| 0s | -2ms | -116.987
| |  P99| 5ms| 0s | -5ms | -101.010
| RoleStore.ChannelHigherScopedPermissions |  Avg| 3ms| 2ms | -1ms | -32.903
| |  P99| 20ms| 5ms | -15ms | -75.934
| RoleStore.GetByNames |  Avg| 2ms| 1ms | -1ms | -46.113
| |  P99| 23ms| 5ms | -18ms | -76.596
| ScheduledPostStore.CreateScheduledPost |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ScheduledPostStore.GetMaxMessageSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetPendingScheduledPosts |  Avg| 5ms| 1ms | -4ms | -87.604
| |  P99| 48ms| 5ms | -43ms | -89.817
| ScheduledPostStore.GetScheduledPostsForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ScheduledPostStore.UpdateOldScheduledPosts |  Avg| 4ms| 2ms | -2ms | -51.226
| |  P99| 46ms| 5ms | -41ms | -89.617
| SessionStore.Get |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 27ms| 24ms | -3ms | -11.136
| SessionStore.GetLRUSessions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 11.503
| SessionStore.GetSessionsExpired |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| SessionStore.Remove |  Avg| 4ms| 3ms | -1ms | -28.022
| |  P99| 9ms| 5ms | -4ms | -42.780
| SessionStore.Save |  Avg| 6ms| 5ms | -1ms | -18.155
| |  P99| 23ms| 23ms | 0s | 0.000
| SessionStore.UpdateLastActivityAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| SharedChannelStore.HasChannel |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 7ms | -1ms | -12.730
| StatusStore.GetByIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.SaveOrUpdate |  Avg| 4ms| 11ms | 7ms | 182.918
| |  P99| 14ms| 180ms | 166ms | 1151.394
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 4ms| 3ms | -1ms | -27.703
| |  P99| 22ms| 8ms | -14ms | -62.361
| StatusStore.UpdateLastActivityAt |  Avg| 3ms| 4ms | 1ms | 28.845
| |  P99| 10ms| 10ms | 0s | 0.000
| SystemStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 16ms| 15ms | -1ms | -6.272
| TeamStore.AnalyticsTeamCount |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetActiveMemberCount |  Avg| 34ms| 34ms | 0s | 0.000
| |  P99| 50ms| 50ms | 0s | 0.000
| TeamStore.GetAllPage |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| TeamStore.GetByName |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 0s | -5ms | -101.010
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 11ms| 10ms | -1ms | -8.922
| TeamStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 12ms| 13ms | 1ms | 8.145
| TeamStore.GetTeamsByUserId |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 11.711
| TeamStore.GetTeamsForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 13ms| 13ms | 0s | 0.000
| TeamStore.GetTotalMemberCount |  Avg| 17ms| 17ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| TeamStore.SaveMember |  Avg| 23ms| 23ms | 0s | 0.000
| |  P99| 62ms| 62ms | 0s | 0.000
| ThreadStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetMembershipForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -17.239
| ThreadStore.GetTeamsUnreadForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 11ms| 10ms | -1ms | -9.318
| ThreadStore.GetThreadFollowers |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetThreadForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ThreadStore.GetThreadsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 10.716
| ThreadStore.GetTotalThreads |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 11.966
| ThreadStore.GetTotalUnreadMentions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ThreadStore.GetTotalUnreadThreads |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.047
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.760
| ThreadStore.MaintainMembership |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| ThreadStore.MarkAllAsReadByChannels |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.579
| ThreadStore.MarkAllAsReadByTeam |  Avg| 5ms| 4ms | -1ms | -20.339
| |  P99| 25ms| 5ms | -20ms | -81.466
| ThreadStore.MarkAsRead |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ThreadStore.UpdateMembership |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.440
| TokenStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AnalyticsActiveCount |  Avg| 13ms| 14ms | 1ms | 7.707
| |  P99| 25ms| 25ms | 0s | 0.000
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AutocompleteUsersInChannel |  Avg| 35ms| 35ms | 0s | 0.000
| |  P99| 178ms| 178ms | 0s | 0.000
| UserStore.Count |  Avg| 10ms| 9ms | -1ms | -9.665
| |  P99| 45ms| 24ms | -21ms | -47.191
| UserStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 11ms| 11ms | 0s | 0.000
| UserStore.GetAllProfiles |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| UserStore.GetAllProfilesInChannel |  Avg| 143ms| 145ms | 2ms | 1.400
| |  P99| 465ms| 466ms | 1ms | 0.215
| UserStore.GetByUsername |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 10ms | 3ms | 43.322
| UserStore.GetForLogin |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 11ms| 9ms | -2ms | -18.670
| UserStore.GetMany |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfileByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 11ms| 13ms | 2ms | 18.317
| UserStore.GetProfilesByUsernames |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfilesInChannel |  Avg| 62ms| 9ms | -53ms | -84.933
| |  P99| 247ms| 10ms | -237ms | -95.951
| UserStore.GetProfilesNotInChannel |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetUnreadCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -10.962
| UserStore.IsEmpty |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.Save |  Avg| 69ms| 69ms | 0s | 0.000
| |  P99| 193ms| 189ms | -4ms | -2.077
| UserStore.Search |  Avg| 26ms| 26ms | 0s | 0.000
| |  P99| 50ms| 50ms | 0s | 0.000
| UserStore.Update |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 35ms| 35ms | 0s | 0.000
| UserStore.UpdateFailedPasswordAttempts |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| UserStore.UpdateLastLogin |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 20ms| 21ms | 1ms | 4.901
| UserStore.UpdateUpdateAt |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 21ms| 21ms | 0s | 0.000
| UserTermsOfServiceStore.GetByUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| WebhookStore.GetOutgoingByTeam |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 29ms| 25ms | -4ms | -13.663
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 164ms| 153ms | -11ms | -6.716
| | P99| 416ms| 422ms | 6ms | 1.443
| addTeamMember | Avg| 546ms| 553ms | 7ms | 1.281
| | P99| 1.679s| 1.585s | -94ms | -5.599
| autocompleteChannelsForTeamForSearch | Avg| 30ms| 22ms | -8ms | -26.691
| | P99| 95ms| 47ms | -48ms | -50.313
| autocompleteUsers | Avg| 32ms| 32ms | 0s | 0.000
| | P99| 156ms| 157ms | 1ms | 0.639
| createCategoryForTeamForUser | Avg| 30ms| 33ms | 3ms | 9.975
| | P99| 50ms| 50ms | 0s | 0.000
| createChannel | Avg| 198ms| 177ms | -21ms | -10.592
| | P99| 249ms| 248ms | -1ms | -0.402
| createChannelBookmark | Avg| 17ms| 26ms | 9ms | 53.847
| | P99| 25ms| 98ms | 73ms | 293.763
| createDirectChannel | Avg| 173ms| 161ms | -12ms | -6.925
| | P99| 474ms| 466ms | -8ms | -1.688
| createGroupChannel | Avg| 255ms| 265ms | 10ms | 3.916
| | P99| 495ms| 496ms | 1ms | 0.202
| createPost | Avg| 166ms| 168ms | 2ms | 1.208
| | P99| 685ms| 697ms | 12ms | 1.752
| createSchedulePost | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| createUser | Avg| 115ms| 114ms | -1ms | -0.871
| | P99| 321ms| 271ms | -50ms | -15.556
| deleteChannelBookmark | Avg| 17ms| 18ms | 1ms | 5.730
| | P99| 25ms| 25ms | 0s | 0.000
| deleteDraft | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 7ms| 6ms | -1ms | -14.984
| deletePost | Avg| 19ms| 20ms | 1ms | 5.262
| | P99| 25ms| 25ms | 0s | 0.000
| followThreadByUser | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| getAllTeams | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 13ms| 13ms | 0s | 0.000
| getAnalytics | Avg| 38ms| 40ms | 2ms | 5.329
| | P99| 50ms| 50ms | 0s | 0.000
| getCategoriesForTeamForUser | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 35ms| 38ms | 3ms | 8.640
| getChannel | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getChannelByNameForTeamName | Avg| 1ms| 0s | -1ms | -97.520
| | P99| 5ms| 0s | -5ms | -101.010
| getChannelMember | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 38ms| 36ms | -2ms | -5.225
| getChannelMembers | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getChannelMembersForTeamForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 11ms| 11ms | 0s | 0.000
| getChannelMembersForUser | Avg| 5ms| 6ms | 1ms | 19.138
| | P99| 10ms| 10ms | 0s | 0.000
| getChannelStats | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| getChannelUnread | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 8ms | 3ms | 60.606
| getChannelsForTeamForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| getChannelsForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 22ms| 22ms | 0s | 0.000
| getClientConfig | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 31ms| 32ms | 1ms | 3.200
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getDrafts | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 8ms| 6ms | -2ms | -24.779
| getFilePreview | Avg| 38ms| 38ms | 0s | 0.000
| | P99| 97ms| 98ms | 1ms | 1.027
| getFileThumbnail | Avg| 30ms| 31ms | 1ms | 3.282
| | P99| 87ms| 89ms | 2ms | 2.288
| getFilteredUsersStats | Avg| 9ms| 10ms | 1ms | 11.039
| | P99| 10ms| 25ms | 15ms | 150.720
| getGroups | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getGroupsAssociatedToChannelsByTeam | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getJobsByType | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getPostThread | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 21ms| 18ms | -3ms | -14.241
| getPostsForChannel | Avg| 12ms| 12ms | 0s | 0.000
| | P99| 90ms| 89ms | -1ms | -1.114
| getPostsForChannelAroundLastUnread | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 47ms| 46ms | -1ms | -2.125
| getPreferences | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 17ms| 17ms | 0s | 0.000
| getPrevTrialLicense | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getProductNotices | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getProfileImage | Avg| 78ms| 76ms | -2ms | -2.563
| | P99| 348ms| 338ms | -10ms | -2.870
| getPublicChannelsForTeam | Avg| 13ms| 13ms | 0s | 0.000
| | P99| 38ms| 25ms | -13ms | -34.085
| getRolesByNames | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getServerLimits | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 0s | -5ms | -101.010
| getTeamMember | Avg| 2ms| 3ms | 1ms | 40.526
| | P99| 5ms| 12ms | 7ms | 140.067
| getTeamMembersForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 20ms| 19ms | -1ms | -5.035
| getTeamScheduledPosts | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 17ms| 19ms | 2ms | 11.486
| getTeamStats | Avg| 34ms| 34ms | 0s | 0.000
| | P99| 50ms| 50ms | 0s | 0.000
| getTeamsForUser | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 9ms| 10ms | 1ms | 11.547
| getTeamsUnreadForUser | Avg| 3ms| 2ms | -1ms | -39.827
| | P99| 19ms| 19ms | 0s | 0.000
| getThreadsForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 10ms| 13ms | 3ms | 29.502
| getUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 19ms| 18ms | -1ms | -5.242
| getUserByUsername | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 20ms| 20ms | 0s | 0.000
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsersByNames | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 6ms | 1ms | 18.690
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| listChannelBookmarksForChannel | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| login | Avg| 57ms| 58ms | 1ms | 1.744
| | P99| 243ms| 243ms | 0s | 0.000
| logout | Avg| 23ms| 25ms | 2ms | 8.744
| | P99| 48ms| 49ms | 1ms | 2.067
| patchPost | Avg| 19ms| 20ms | 1ms | 5.213
| | P99| 45ms| 46ms | 1ms | 2.232
| removeUserCustomStatus | Avg| 112ms| 125ms | 13ms | 11.627
| | P99| 248ms| 248ms | 0s | 0.000
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 24ms| 23ms | -1ms | -4.181
| searchAllChannels | Avg| 31ms| 32ms | 1ms | 3.208
| | P99| 98ms| 98ms | 0s | 0.000
| searchGroupChannels | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 14ms| 10ms | -4ms | -28.844
| searchPostsInTeam | Avg| 30ms| 31ms | 1ms | 3.303
| | P99| 624ms| 588ms | -36ms | -5.767
| searchUsers | Avg| 27ms| 27ms | 0s | 0.000
| | P99| 50ms| 50ms | 0s | 0.000
| setPostReminder | Avg| 15ms| 15ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 11ms| 12ms | 1ms | 8.838
| | P99| 25ms| 38ms | 13ms | 52.332
| updateCategoriesForTeamForUser | Avg| 61ms| 73ms | 12ms | 19.755
| | P99| 218ms| 240ms | 22ms | 10.069
| updatePreferences | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| updateReadStateAllThreadsByUser | Avg| 5ms| 4ms | -1ms | -19.992
| | P99| 25ms| 5ms | -20ms | -81.466
| updateReadStateThreadByUser | Avg| 29ms| 28ms | -1ms | -3.470
| | P99| 73ms| 64ms | -9ms | -12.326
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 386ms| 386ms | 0s | 0.000
| | P99| 988ms| 987ms | -1ms | -0.101
| upsertDraft | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 17ms| 15ms | -2ms | -11.488
| viewChannel | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
