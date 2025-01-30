### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ComplianceStore.MessageExport | avg | 2ms | 97ms | 95ms | 5313.30
| StatusStore.SaveOrUpdate | avg | 3ms | 6ms | 3ms | 116.77
| PostStore.AnalyticsPostCount | avg | 455ms | 619ms | 164ms | 36.04
| DraftStore.DeleteDraftsAssociatedWithPost | avg | 13ms | 15ms | 2ms | 14.92
| UserStore.Count | avg | 64ms | 70ms | 6ms | 9.42
| ChannelStore.GetMemberCount | avg | 73ms | 78ms | 5ms | 6.81
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ComplianceStore.MessageExport | p99 | 6ms | 247ms | 241ms | 3866.31
| StatusStore.SaveOrUpdate | p99 | 9ms | 107ms | 98ms | 1136.57
| StatusStore.UpdateExpiredDNDStatuses | p99 | 5ms | 20ms | 15ms | 303.03
| DraftStore.DeleteDraftsAssociatedWithPost | p99 | 25ms | 91ms | 66ms | 266.40
| RoleStore.GetByNames | p99 | 5ms | 15ms | 10ms | 202.02
| ChannelBookmarkStore.Save | p99 | 10ms | 24ms | 14ms | 141.10
| JobStore.GetCountByStatusAndType | p99 | 11ms | 26ms | 15ms | 135.75
| CommandWebhookStore.Cleanup | p99 | 5ms | 10ms | 5ms | 101.01
| LinkMetadataStore.Save | p99 | 8ms | 15ms | 7ms | 89.75
| ChannelStore.UpdateSidebarCategories | p99 | 25ms | 46ms | 21ms | 84.51
| JobStore.Save | p99 | 6ms | 11ms | 5ms | 83.33
| ChannelStore.GetSidebarCategory | p99 | 5ms | 9ms | 4ms | 80.81
| PostPersistentNotificationStore.Get | p99 | 8ms | 14ms | 6ms | 79.47
| ClusterDiscoveryStore.SetLastPingAt | p99 | 7ms | 11ms | 4ms | 53.87
| PostStore.GetPostReminderMetadata | p99 | 5ms | 7ms | 2ms | 40.40
| FileInfoStore.SetContent | p99 | 15ms | 21ms | 6ms | 40.14
| JobStore.UpdateStatus | p99 | 8ms | 10ms | 2ms | 25.00
| UserStore.Count | p99 | 212ms | 239ms | 27ms | 12.71
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 82ms | 91ms | 9ms | 11.00
| ProductNoticesStore.View | p99 | 86ms | 89ms | 3ms | 3.49
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelMemberHistoryStore.GetUsersInChannelDuring | avg | 210ms | 168ms | -42ms | -20.02
| PostStore.SearchPostsForUser | avg | 48ms | 39ms | -9ms | -18.93
| PostStore.Update | avg | 12ms | 10ms | -2ms | -17.32
| ChannelStore.AutocompleteInTeamForSearch | avg | 159ms | 147ms | -12ms | -7.53
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| BotStore.GetAll | p99 | 5ms | 0s | -5ms | -101.01
| RetentionPolicyStore.GetCount | p99 | 5ms | 0s | -5ms | -101.01
| RetentionPolicyStore.GetAll | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.GetMemberCountsByGroup | p99 | 5ms | 0s | -5ms | -101.01
| PostStore.GetPostReminders | p99 | 20ms | 10ms | -10ms | -48.78
| UserStore.GetProfilesInChannel | p99 | 9ms | 5ms | -4ms | -45.71
| ChannelStore.GetTeamChannels | p99 | 46ms | 25ms | -21ms | -45.39
| PostStore.SearchPostsForUser | p99 | 596ms | 336ms | -260ms | -43.60
| PostStore.Update | p99 | 40ms | 25ms | -15ms | -37.50
| JobStore.GetAllByStatus | p99 | 11ms | 7ms | -4ms | -35.77
| ScheduledPostStore.UpdateOldScheduledPosts | p99 | 8ms | 5ms | -3ms | -35.29
| PostStore.GetPostsAfter | p99 | 7ms | 5ms | -2ms | -28.89
| PluginStore.List | p99 | 7ms | 5ms | -2ms | -28.57
| ChannelStore.Save | p99 | 68ms | 49ms | -19ms | -27.74
| UserStore.GetByUsername | p99 | 7ms | 5ms | -2ms | -27.12
| ChannelStore.GetGuestCount | p99 | 8ms | 6ms | -2ms | -26.32
| UserStore.UpdateLastLogin | p99 | 8ms | 6ms | -2ms | -26.29
| DraftStore.Delete | p99 | 8ms | 6ms | -2ms | -25.21
| UserStore.GetAllProfiles | p99 | 8ms | 6ms | -2ms | -24.33
| ChannelMemberHistoryStore.GetUsersInChannelDuring | p99 | 312ms | 249ms | -63ms | -20.20
| ChannelStore.GetMembersForUserWithPagination | p99 | 24ms | 21ms | -3ms | -12.45
| PreferenceStore.Save | p99 | 19ms | 17ms | -2ms | -10.61
| UserStore.AutocompleteUsersInChannel | p99 | 366ms | 339ms | -27ms | -7.38
| ChannelStore.SaveMember | p99 | 48ms | 46ms | -2ms | -4.16
| ChannelStore.AutocompleteInTeamForSearch | p99 | 2.041s | 1.98s | -61ms | -2.99
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| deleteChannelBookmark | avg | 7ms | 51ms | 44ms | 654.38
| createChannelBookmark | avg | 14ms | 16ms | 2ms | 14.50
| createChannel | avg | 172ms | 190ms | 18ms | 10.49
| updateCategoriesForTeamForUser | avg | 19ms | 21ms | 2ms | 10.37
| createGroupChannel | avg | 206ms | 222ms | 16ms | 7.77
| createDirectChannel | avg | 150ms | 158ms | 8ms | 5.32
| addChannelMember | avg | 133ms | 140ms | 7ms | 5.24
| autocompleteUsers | avg | 125ms | 128ms | 3ms | 2.40
| uploadFileStream | avg | 344ms | 351ms | 7ms | 2.04
| createUser | avg | 120ms | 122ms | 2ms | 1.66
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| deleteChannelBookmark | p99 | 25ms | 100ms | 75ms | 303.65
| createChannelBookmark | p99 | 25ms | 94ms | 69ms | 278.00
| updateCategoriesForTeamForUser | p99 | 25ms | 46ms | 21ms | 84.51
| unfollowThreadByUser | p99 | 15ms | 23ms | 8ms | 52.20
| removeUserCustomStatus | p99 | 275ms | 338ms | 63ms | 22.91
| logout | p99 | 44ms | 49ms | 5ms | 11.43
| createDirectChannel | p99 | 442ms | 466ms | 24ms | 5.43
| uploadFileStream | p99 | 965ms | 976ms | 11ms | 1.14
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| updateChannelBookmark | avg | 14ms | 7ms | -7ms | -51.56
| searchPostsInTeam | avg | 51ms | 43ms | -8ms | -15.67
| getProfileImage | avg | 70ms | 64ms | -6ms | -8.55
| autocompleteChannelsForTeamForSearch | avg | 159ms | 147ms | -12ms | -7.53
| addTeamMember | avg | 634ms | 613ms | -21ms | -3.31
| createPost | avg | 203ms | 199ms | -4ms | -1.97
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| channelMemberCountsByGroup | p99 | 5ms | 0s | -5ms | -101.01
| searchPostsInTeam | p99 | 628ms | 336ms | -292ms | -46.47
| createChannel | p99 | 462ms | 249ms | -213ms | -46.05
| getChannel | p99 | 13ms | 7ms | -6ms | -44.86
| getAllTeams | p99 | 7ms | 5ms | -2ms | -30.39
| getChannelMember | p99 | 16ms | 12ms | -4ms | -25.41
| addChannelMember | p99 | 366ms | 285ms | -81ms | -22.15
| getPreferences | p99 | 10ms | 8ms | -2ms | -20.92
| patchPost | p99 | 48ms | 43ms | -5ms | -10.44
| autocompleteUsers | p99 | 327ms | 297ms | -30ms | -9.16
| getPostsForChannelAroundLastUnread | p99 | 43ms | 40ms | -3ms | -6.92
| updateReadStateThreadByUser | p99 | 39ms | 37ms | -2ms | -5.18
| addTeamMember | p99 | 2.337s | 2.26s | -77ms | -3.29
| autocompleteChannelsForTeamForSearch | p99 | 2.041s | 1.98s | -61ms | -2.99
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 11ms| 11ms | 0s | 0.000
| BotStore.Get |  Avg| 1ms| 2ms | 1ms | 76.259
| |  P99| 5ms| 5ms | 0s | 0.000
| BotStore.GetAll |  Avg| 1ms| 0s | -1ms | -110.176
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelBookmarkStore.Delete |  Avg| 4ms| 3ms | -1ms | -28.198
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelBookmarkStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelBookmarkStore.Save |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 10ms| 24ms | 14ms | 141.100
| ChannelMemberHistoryStore.GetUsersInChannelDuring |  Avg| 210ms| 168ms | -42ms | -20.016
| |  P99| 312ms| 249ms | -63ms | -20.198
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 7ms | -1ms | -12.362
| ChannelStore.AnalyticsTypeCount |  Avg| 3ms| 4ms | 1ms | 30.084
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.Autocomplete |  Avg| 954ms| 963ms | 9ms | 0.943
| |  P99| 2.459s| 2.461s | 2ms | 0.081
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 159ms| 147ms | -12ms | -7.533
| |  P99| 2.041s| 1.98s | -61ms | -2.988
| ChannelStore.CreateDirectChannel |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.CreateInitialSidebarCategories |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.CreateSidebarCategory |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ChannelStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetAllChannelMembersForUser |  Avg| 2ms| 1ms | -1ms | -65.023
| |  P99| 8ms| 7ms | -1ms | -12.349
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 11ms| 10ms | -1ms | -9.384
| |  P99| 82ms| 91ms | 9ms | 10.998
| ChannelStore.GetByName |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 22ms | -1ms | -4.323
| ChannelStore.GetChannelUnread |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannels |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannelsByUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetFileCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ChannelStore.GetGuestCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 6ms | -2ms | -26.323
| ChannelStore.GetMember |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ChannelStore.GetMemberCount |  Avg| 73ms| 78ms | 5ms | 6.813
| |  P99| 247ms| 247ms | 0s | 0.000
| ChannelStore.GetMemberCountsByGroup |  Avg| 1ms| 0s | -1ms | -101.860
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelStore.GetMemberForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMemberLastViewedAt |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMembersForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMembersForUserWithPagination |  Avg| 10ms| 9ms | -1ms | -10.305
| |  P99| 24ms| 21ms | -3ms | -12.448
| ChannelStore.GetPinnedPostCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 6ms | 1ms | 20.058
| ChannelStore.GetPublicChannelsForTeam |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 16ms| 16ms | 0s | 0.000
| ChannelStore.GetSidebarCategory |  Avg| 2ms| 3ms | 1ms | 41.346
| |  P99| 5ms| 9ms | 4ms | 80.808
| ChannelStore.GetTeamChannels |  Avg| 23ms| 22ms | -1ms | -4.435
| |  P99| 46ms| 25ms | -21ms | -45.392
| ChannelStore.IncrementMentionCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.IsReadOnlyChannel |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.Save |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 68ms| 49ms | -19ms | -27.738
| ChannelStore.SaveMember |  Avg| 17ms| 17ms | 0s | 0.000
| |  P99| 48ms| 46ms | -2ms | -4.157
| ChannelStore.SearchGroupChannels |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 6ms | 1ms | 20.069
| ChannelStore.UpdateLastViewedAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ChannelStore.UpdateSidebarCategories |  Avg| 13ms| 14ms | 1ms | 7.638
| |  P99| 25ms| 46ms | 21ms | 84.507
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 11ms | 4ms | 53.873
| CommandWebhookStore.Cleanup |  Avg| 1ms| 2ms | 1ms | 143.638
| |  P99| 5ms| 10ms | 5ms | 101.010
| ComplianceStore.MessageExport |  Avg| 2ms| 97ms | 95ms | 5313.299
| |  P99| 6ms| 247ms | 241ms | 3866.310
| DesktopTokensStore.DeleteOlderThan |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Delete |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 6ms | -2ms | -25.210
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 13ms| 15ms | 2ms | 14.920
| |  P99| 25ms| 91ms | 66ms | 266.398
| DraftStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.GetDraftsForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Upsert |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| EmojiStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| EmojiStore.GetMultipleByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.AttachToPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| FileInfoStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.GetByIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -15.487
| FileInfoStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| FileInfoStore.SetContent |  Avg| 6ms| 5ms | -1ms | -17.817
| |  P99| 15ms| 21ms | 6ms | 40.135
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| GroupStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -17.471
| GroupStore.GetGroups |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 6ms | 0s | 0.000
| GroupStore.GetGroupsAssociatedToChannelsByTeam |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.GetAllByStatus |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 11ms| 7ms | -4ms | -35.766
| JobStore.GetAllByTypePage |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.GetCountByStatusAndType |  Avg| 1ms| 2ms | 1ms | 85.338
| |  P99| 11ms| 26ms | 15ms | 135.747
| JobStore.GetNewestJobByStatusesAndType |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 6ms| 11ms | 5ms | 83.333
| JobStore.UpdateOptimistically |  Avg| 3ms| 2ms | -1ms | -34.518
| |  P99| 10ms| 10ms | 0s | 0.000
| JobStore.UpdateStatus |  Avg| 3ms| 2ms | -1ms | -39.122
| |  P99| 8ms| 10ms | 2ms | 25.000
| JobStore.UpdateStatusOptimistically |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -10.714
| LicenseStore.GetAll |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Save |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 15ms | 7ms | 89.745
| PluginStore.Delete |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PluginStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PluginStore.List |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 5ms | -2ms | -28.571
| PluginStore.SetWithOptions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| PostAcknowledgementStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostAcknowledgementStore.GetForPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| PostPersistentNotificationStore.DeleteExpired |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 14ms | 6ms | 79.470
| PostPersistentNotificationStore.GetSingle |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPriorityStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPriorityStore.GetForPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| PostStore.AnalyticsPostCount |  Avg| 455ms| 619ms | 164ms | 36.040
| |  P99| 993ms| 993ms | 0s | 0.000
| PostStore.Delete |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 21ms| 22ms | 1ms | 4.673
| PostStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| PostStore.GetEtag |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdBeforeTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostReminderMetadata |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 7ms | 2ms | 40.404
| PostStore.GetPostReminders |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 20ms| 10ms | -10ms | -48.780
| PostStore.GetPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 18ms| 18ms | 0s | 0.000
| PostStore.GetPostsAfter |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 5ms | -2ms | -28.886
| PostStore.GetPostsBefore |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| PostStore.GetPostsByThread |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostsSince |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 46ms| 46ms | 0s | 0.000
| PostStore.GetSingle |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| PostStore.SearchPostsForUser |  Avg| 48ms| 39ms | -9ms | -18.934
| |  P99| 596ms| 336ms | -260ms | -43.603
| PostStore.SetPostReminder |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Update |  Avg| 12ms| 10ms | -2ms | -17.316
| |  P99| 40ms| 25ms | -15ms | -37.501
| PreferenceStore.DeleteCategoryAndName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PreferenceStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| PreferenceStore.GetAll |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -10.686
| PreferenceStore.Save |  Avg| 5ms| 4ms | -1ms | -21.764
| |  P99| 19ms| 17ms | -2ms | -10.614
| ProductNoticesStore.ClearOldNotices |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 16ms| 16ms | 0s | 0.000
| |  P99| 86ms| 89ms | 3ms | 3.486
| ReactionStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| RetentionPolicyStore.GetAll |  Avg| 1ms| 0s | -1ms | -128.245
| |  P99| 5ms| 0s | -5ms | -101.010
| RetentionPolicyStore.GetCount |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 0s | -5ms | -101.010
| RoleStore.ChannelHigherScopedPermissions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| RoleStore.GetByNames |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 15ms | 10ms | 202.020
| ScheduledPostStore.GetPendingScheduledPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 20ms | 0s | 0.000
| ScheduledPostStore.GetScheduledPostsForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.UpdateOldScheduledPosts |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 5ms | -3ms | -35.294
| SchemeStore.GetAllPage |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 11ms| 10ms | -1ms | -9.138
| SessionStore.GetLRUSessions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsExpired |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| SessionStore.Remove |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| SessionStore.UpdateLastActivityAt |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 6ms | -1ms | -14.193
| SharedChannelStore.HasChannel |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.GetByIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 7ms | 1ms | 17.864
| StatusStore.SaveOrUpdate |  Avg| 3ms| 6ms | 3ms | 116.766
| |  P99| 9ms| 107ms | 98ms | 1136.570
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 20ms | 15ms | 303.030
| StatusStore.UpdateLastActivityAt |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 6ms | 1ms | 20.006
| SystemStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.AnalyticsTeamCount |  Avg| 2ms| 1ms | -1ms | -44.235
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetActiveMemberCount |  Avg| 108ms| 108ms | 0s | 0.000
| |  P99| 248ms| 248ms | 0s | 0.000
| TeamStore.GetAllPage |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetMember |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetTeamsByUserId |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetTeamsForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetTotalMemberCount |  Avg| 82ms| 82ms | 0s | 0.000
| |  P99| 100ms| 100ms | 0s | 0.000
| TeamStore.SaveMember |  Avg| 66ms| 67ms | 1ms | 1.509
| |  P99| 100ms| 100ms | 0s | 0.000
| ThreadStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetMembershipForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetTeamsUnreadForUser |  Avg| 2ms| 1ms | -1ms | -64.110
| |  P99| 6ms| 5ms | -1ms | -15.538
| ThreadStore.GetThreadFollowers |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -17.164
| ThreadStore.GetThreadForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetThreadsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetTotalThreads |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetTotalUnreadMentions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ThreadStore.GetTotalUnreadThreads |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.MaintainMembership |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ThreadStore.MarkAllAsReadByChannels |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.MarkAllAsReadByTeam |  Avg| 2ms| 3ms | 1ms | 41.362
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.MarkAsRead |  Avg| 3ms| 2ms | -1ms | -37.298
| |  P99| 7ms| 6ms | -1ms | -13.700
| ThreadStore.UpdateMembership |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| TokenStore.Cleanup |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AnalyticsActiveCount |  Avg| 159ms| 160ms | 1ms | 0.629
| |  P99| 249ms| 249ms | 0s | 0.000
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AutocompleteUsersInChannel |  Avg| 145ms| 146ms | 1ms | 0.692
| |  P99| 366ms| 339ms | -27ms | -7.379
| UserStore.Count |  Avg| 64ms| 70ms | 6ms | 9.423
| |  P99| 212ms| 239ms | 27ms | 12.706
| UserStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetAllProfiles |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 6ms | -2ms | -24.332
| UserStore.GetAllProfilesInChannel |  Avg| 260ms| 259ms | -1ms | -0.384
| |  P99| 500ms| 498ms | -2ms | -0.400
| UserStore.GetByUsername |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 5ms | -2ms | -27.119
| UserStore.GetForLogin |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetMany |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfileByGroupChannelIdsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfileByIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfilesByUsernames |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfilesInChannel |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -45.714
| UserStore.GetProfilesNotInChannel |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetUnreadCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| UserStore.IsEmpty |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.Save |  Avg| 67ms| 66ms | -1ms | -1.488
| |  P99| 100ms| 100ms | 0s | 0.000
| UserStore.Search |  Avg| 62ms| 62ms | 0s | 0.000
| |  P99| 243ms| 243ms | 0s | 0.000
| UserStore.Update |  Avg| 4ms| 3ms | -1ms | -28.067
| |  P99| 9ms| 10ms | 1ms | 11.001
| UserStore.UpdateFailedPasswordAttempts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 10.554
| UserStore.UpdateLastLogin |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 6ms | -2ms | -26.295
| UserStore.UpdateUpdateAt |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| UserTermsOfServiceStore.GetByUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| WebhookStore.GetOutgoingByTeam |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 26ms| 27ms | 1ms | 3.834
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 133ms| 140ms | 7ms | 5.245
| | P99| 366ms| 285ms | -81ms | -22.154
| addTeamMember | Avg| 634ms| 613ms | -21ms | -3.314
| | P99| 2.337s| 2.26s | -77ms | -3.294
| autocompleteChannelsForTeamForSearch | Avg| 159ms| 147ms | -12ms | -7.531
| | P99| 2.041s| 1.98s | -61ms | -2.988
| autocompleteUsers | Avg| 125ms| 128ms | 3ms | 2.395
| | P99| 327ms| 297ms | -30ms | -9.162
| channelMemberCountsByGroup | Avg| 1ms| 0s | -1ms | -90.726
| | P99| 5ms| 0s | -5ms | -101.010
| createCategoryForTeamForUser | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| createChannel | Avg| 172ms| 190ms | 18ms | 10.492
| | P99| 462ms| 249ms | -213ms | -46.054
| createChannelBookmark | Avg| 14ms| 16ms | 2ms | 14.503
| | P99| 25ms| 94ms | 69ms | 278.001
| createDirectChannel | Avg| 150ms| 158ms | 8ms | 5.322
| | P99| 442ms| 466ms | 24ms | 5.429
| createGroupChannel | Avg| 206ms| 222ms | 16ms | 7.768
| | P99| 492ms| 494ms | 2ms | 0.407
| createPost | Avg| 203ms| 199ms | -4ms | -1.969
| | P99| 939ms| 935ms | -4ms | -0.426
| createUser | Avg| 120ms| 122ms | 2ms | 1.660
| | P99| 390ms| 388ms | -2ms | -0.513
| deleteChannelBookmark | Avg| 7ms| 51ms | 44ms | 654.383
| | P99| 25ms| 100ms | 75ms | 303.649
| deleteDraft | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 6ms| 5ms | -1ms | -17.943
| deletePost | Avg| 11ms| 10ms | -1ms | -9.226
| | P99| 25ms| 25ms | 0s | 0.000
| followThreadByUser | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| getAllTeams | Avg| 2ms| 1ms | -1ms | -66.629
| | P99| 7ms| 5ms | -2ms | -30.386
| getCategoriesForTeamForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 16ms| 16ms | 0s | 0.000
| getChannel | Avg| 3ms| 2ms | -1ms | -37.979
| | P99| 13ms| 7ms | -6ms | -44.858
| getChannelMember | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 16ms| 12ms | -4ms | -25.413
| getChannelMembersForTeamForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getChannelStats | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 215ms| 217ms | 2ms | 0.930
| getChannelUnread | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getChannelsForTeamForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 6ms| 5ms | -1ms | -15.923
| getChannelsForUser | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getClientConfig | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 10ms| 9ms | -1ms | -10.517
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getDrafts | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getFilePreview | Avg| 36ms| 36ms | 0s | 0.000
| | P99| 92ms| 92ms | 0s | 0.000
| getFileThumbnail | Avg| 30ms| 30ms | 0s | 0.000
| | P99| 83ms| 83ms | 0s | 0.000
| getJobsByType | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getPostThread | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 22ms| 21ms | -1ms | -4.641
| getPostsForChannel | Avg| 15ms| 14ms | -1ms | -6.839
| | P99| 96ms| 96ms | 0s | 0.000
| getPostsForChannelAroundLastUnread | Avg| 12ms| 11ms | -1ms | -8.608
| | P99| 43ms| 40ms | -3ms | -6.921
| getPreferences | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 10ms| 8ms | -2ms | -20.915
| getPrevTrialLicense | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getProfileImage | Avg| 70ms| 64ms | -6ms | -8.546
| | P99| 249ms| 248ms | -1ms | -0.402
| getPublicChannelsForTeam | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| getRolesByNames | Avg| 1ms| 0s | -1ms | -131.191
| | P99| 5ms| 5ms | 0s | 0.000
| getTeamMember | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getTeamMembersForUser | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 6ms| 6ms | 0s | 0.000
| getTeamStats | Avg| 108ms| 108ms | 0s | 0.000
| | P99| 248ms| 248ms | 0s | 0.000
| getTeamsForUser | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getTeamsUnreadForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 10ms| 9ms | -1ms | -10.328
| getThreadsForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 6ms| 6ms | 0s | 0.000
| getUser | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 7ms| 7ms | 0s | 0.000
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 9ms | -1ms | -10.302
| getUsersByGroupChannelIds | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsersByNames | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| listChannelBookmarksForChannel | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| login | Avg| 57ms| 58ms | 1ms | 1.747
| | P99| 228ms| 226ms | -2ms | -0.879
| logout | Avg| 21ms| 22ms | 1ms | 4.742
| | P99| 44ms| 49ms | 5ms | 11.429
| patchPost | Avg| 19ms| 18ms | -1ms | -5.129
| | P99| 48ms| 43ms | -5ms | -10.441
| removeUserCustomStatus | Avg| 108ms| 109ms | 1ms | 0.925
| | P99| 275ms| 338ms | 63ms | 22.909
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 12ms| 13ms | 1ms | 8.416
| searchAllChannels | Avg| 955ms| 963ms | 8ms | 0.838
| | P99| 2.459s| 2.461s | 2ms | 0.081
| searchGroupChannels | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 6ms | 1ms | 20.069
| searchPostsInTeam | Avg| 51ms| 43ms | -8ms | -15.673
| | P99| 628ms| 336ms | -292ms | -46.468
| searchUsers | Avg| 63ms| 63ms | 0s | 0.000
| | P99| 243ms| 243ms | 0s | 0.000
| setPostReminder | Avg| 9ms| 8ms | -1ms | -11.342
| | P99| 24ms| 24ms | 0s | 0.000
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 15ms| 23ms | 8ms | 52.203
| updateCategoriesForTeamForUser | Avg| 19ms| 21ms | 2ms | 10.373
| | P99| 25ms| 46ms | 21ms | 84.507
| updateChannelBookmark | Avg| 14ms| 7ms | -7ms | -51.564
| | P99| 25ms| 25ms | 0s | 0.000
| updatePreferences | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| updateReadStateAllThreadsByUser | Avg| 2ms| 3ms | 1ms | 40.017
| | P99| 5ms| 5ms | 0s | 0.000
| updateReadStateThreadByUser | Avg| 15ms| 14ms | -1ms | -6.845
| | P99| 39ms| 37ms | -2ms | -5.184
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 344ms| 351ms | 7ms | 2.037
| | P99| 965ms| 976ms | 11ms | 1.140
| upsertDraft | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 9ms| 9ms | 0s | 0.000
| viewChannel | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 24ms| 23ms | -1ms | -4.182
