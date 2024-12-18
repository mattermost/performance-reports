### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 13ms | 15ms | 2ms | 15.24
| ChannelStore.UpdateSidebarCategories | avg | 38ms | 40ms | 2ms | 5.33
| PostStore.SearchPostsForUser | avg | 58ms | 61ms | 3ms | 5.16
| UserStore.Count | avg | 48ms | 50ms | 2ms | 4.15
| ChannelStore.GetMemberCount | avg | 62ms | 64ms | 2ms | 3.20
| UserStore.AnalyticsActiveCount | avg | 150ms | 154ms | 4ms | 2.67
| UserStore.GetAllProfilesInChannel | avg | 188ms | 192ms | 4ms | 2.13
| TeamStore.GetActiveMemberCount | avg | 100ms | 102ms | 2ms | 1.99
| ChannelStore.Autocomplete | avg | 944ms | 956ms | 12ms | 1.27
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| JobStore.UpdateStatusOptimistically | p99 | 9ms | 18ms | 9ms | 95.23
| ComplianceStore.MessageExport | p99 | 5ms | 9ms | 4ms | 80.81
| ChannelStore.GetPublicChannelsForTeam | p99 | 11ms | 19ms | 8ms | 74.21
| ClusterDiscoveryStore.SetLastPingAt | p99 | 8ms | 12ms | 4ms | 49.23
| ChannelStore.CreateDirectChannel | p99 | 25ms | 37ms | 12ms | 48.29
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 13ms | 16ms | 3ms | 23.63
| PostStore.Update | p99 | 25ms | 29ms | 4ms | 16.10
| ChannelStore.GetByName | p99 | 14ms | 16ms | 2ms | 14.31
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 86ms | 97ms | 11ms | 12.82
| PreferenceStore.Save | p99 | 32ms | 35ms | 3ms | 9.51
| UserStore.AutocompleteUsersInChannel | p99 | 369ms | 381ms | 12ms | 3.25
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.AutocompleteInTeamForSearch | avg | 296ms | 242ms | -54ms | -18.22
| ChannelStore.GetTeamChannels | avg | 24ms | 20ms | -4ms | -16.48
| ChannelMemberHistoryStore.GetUsersInChannelDuring | avg | 200ms | 197ms | -3ms | -1.50
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.GetMembers | p99 | 5ms | 0s | -5ms | -101.01
| BotStore.GetAll | p99 | 5ms | 0s | -5ms | -101.01
| PostStore.SearchPostsForUser | p99 | 535ms | 248ms | -287ms | -53.63
| ChannelStore.GetMembersForUserWithPagination | p99 | 21ms | 10ms | -11ms | -51.40
| JobStore.GetNewestJobByStatusesAndType | p99 | 10ms | 5ms | -5ms | -50.76
| ChannelStore.GetTeamChannels | p99 | 49ms | 25ms | -24ms | -48.73
| LinkMetadataStore.Save | p99 | 9ms | 5ms | -4ms | -45.94
| BotStore.Get | p99 | 9ms | 5ms | -4ms | -43.72
| ChannelStore.AutocompleteInTeamForSearch | p99 | 3.3s | 2.368s | -932ms | -28.24
| UserStore.UpdateLastLogin | p99 | 15ms | 12ms | -3ms | -19.47
| ChannelStore.GetPinnedPostCount | p99 | 17ms | 14ms | -3ms | -17.54
| UserStore.UpdateUpdateAt | p99 | 17ms | 15ms | -2ms | -11.85
| FileInfoStore.AttachToPost | p99 | 17ms | 15ms | -2ms | -11.45
| ChannelStore.Save | p99 | 48ms | 46ms | -2ms | -4.21
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| logout | avg | 19ms | 21ms | 2ms | 10.58
| updateCategoriesForTeamForUser | avg | 47ms | 50ms | 3ms | 6.41
| createChannel | avg | 159ms | 169ms | 10ms | 6.28
| searchPostsInTeam | avg | 62ms | 64ms | 2ms | 3.24
| autocompleteUsers | avg | 110ms | 113ms | 3ms | 2.73
| getTeamStats | avg | 100ms | 102ms | 2ms | 1.99
| searchAllChannels | avg | 945ms | 957ms | 12ms | 1.27
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| logout | p99 | 25ms | 49ms | 24ms | 96.58
| getPublicChannelsForTeam | p99 | 11ms | 19ms | 8ms | 74.21
| addTeamMember | p99 | 997ms | 1.397s | 400ms | 40.10
| getCategoriesForTeamForUser | p99 | 13ms | 16ms | 3ms | 22.82
| autocompleteUsers | p99 | 323ms | 346ms | 23ms | 7.12
| getChannelsForUser | p99 | 184ms | 189ms | 5ms | 2.72
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getTeamScheduledPosts | avg | 2ms | 0s | -2ms | -129.37
| getChannelMembers | avg | 2ms | 0s | -2ms | -111.19
| getFilteredUsersStats | avg | 38ms | 17ms | -21ms | -55.30
| autocompleteChannelsForTeamForSearch | avg | 296ms | 242ms | -54ms | -18.22
| removeUserCustomStatus | avg | 96ms | 81ms | -15ms | -15.58
| createDirectChannel | avg | 153ms | 135ms | -18ms | -11.79
| getProfileImage | avg | 85ms | 79ms | -6ms | -7.09
| getAnalytics | avg | 227ms | 213ms | -14ms | -6.16
| uploadFileStream | avg | 403ms | 386ms | -17ms | -4.22
| createGroupChannel | avg | 217ms | 211ms | -6ms | -2.76
| addChannelMember | avg | 135ms | 133ms | -2ms | -1.48
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getServerLimits | p99 | 5ms | 0s | -5ms | -101.01
| getChannelMembers | p99 | 5ms | 0s | -5ms | -101.01
| getTeamScheduledPosts | p99 | 5ms | 0s | -5ms | -101.01
| getFilteredUsersStats | p99 | 98ms | 25ms | -73ms | -74.49
| followThreadByUser | p99 | 24ms | 10ms | -14ms | -58.82
| autocompleteChannelsForTeamForSearch | p99 | 3.3s | 2.368s | -932ms | -28.24
| searchPostsInTeam | p99 | 535ms | 399ms | -136ms | -25.41
| patchPost | p99 | 46ms | 40ms | -6ms | -13.07
| getProfileImage | p99 | 384ms | 334ms | -50ms | -13.02
| getPostsForChannel | p99 | 77ms | 74ms | -3ms | -3.92
| createGroupChannel | p99 | 490ms | 483ms | -7ms | -1.43
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 20ms| 20ms | 0s | 0.000
| BotStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -43.716
| BotStore.GetAll |  Avg| 1ms| 0s | -1ms | -179.636
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelBookmarkStore.Delete |  Avg| 5ms| 6ms | 1ms | 19.845
| |  P99| 10ms| 10ms | 0s | 0.000
| ChannelBookmarkStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelBookmarkStore.Save |  Avg| 12ms| 11ms | -1ms | -8.351
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelMemberHistoryStore.GetUsersInChannelDuring |  Avg| 200ms| 197ms | -3ms | -1.499
| |  P99| 249ms| 249ms | 0s | 0.000
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 14ms| 15ms | 1ms | 6.918
| ChannelStore.AnalyticsTypeCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.Autocomplete |  Avg| 944ms| 956ms | 12ms | 1.271
| |  P99| 2.459s| 2.46s | 1ms | 0.041
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 296ms| 242ms | -54ms | -18.220
| |  P99| 3.3s| 2.368s | -932ms | -28.238
| ChannelStore.CreateDirectChannel |  Avg| 18ms| 18ms | 0s | 0.000
| |  P99| 25ms| 37ms | 12ms | 48.290
| ChannelStore.CreateInitialSidebarCategories |  Avg| 20ms| 19ms | -1ms | -5.108
| |  P99| 47ms| 47ms | 0s | 0.000
| ChannelStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetAllChannelMembersForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 6ms | 1ms | 19.064
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 13ms| 15ms | 2ms | 15.244
| |  P99| 86ms| 97ms | 11ms | 12.824
| ChannelStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 14ms| 16ms | 2ms | 14.313
| ChannelStore.GetChannelUnread |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannels |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannelsByUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 46ms| 46ms | 0s | 0.000
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetFileCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetGuestCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ChannelStore.GetMemberCount |  Avg| 62ms| 64ms | 2ms | 3.201
| |  P99| 246ms| 246ms | 0s | 0.000
| ChannelStore.GetMemberForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMemberLastViewedAt |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMembers |  Avg| 1ms| 0s | -1ms | -67.385
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelStore.GetMembersForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMembersForUserWithPagination |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 21ms| 10ms | -11ms | -51.398
| ChannelStore.GetPinnedPostCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 17ms| 14ms | -3ms | -17.538
| ChannelStore.GetPublicChannelsForTeam |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 11ms| 19ms | 8ms | 74.207
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 13ms| 16ms | 3ms | 23.633
| ChannelStore.GetSidebarCategory |  Avg| 4ms| 5ms | 1ms | 23.087
| |  P99| 10ms| 10ms | 0s | 0.000
| ChannelStore.GetTeamChannels |  Avg| 24ms| 20ms | -4ms | -16.476
| |  P99| 49ms| 25ms | -24ms | -48.731
| ChannelStore.IncrementMentionCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| ChannelStore.IsReadOnlyChannel |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.Save |  Avg| 12ms| 11ms | -1ms | -8.326
| |  P99| 48ms| 46ms | -2ms | -4.206
| ChannelStore.SaveMember |  Avg| 20ms| 20ms | 0s | 0.000
| |  P99| 49ms| 49ms | 0s | 0.000
| ChannelStore.SearchGroupChannels |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.UpdateLastViewedAt |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ChannelStore.UpdateSidebarCategories |  Avg| 38ms| 40ms | 2ms | 5.330
| |  P99| 232ms| 232ms | 0s | 0.000
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 8ms| 12ms | 4ms | 49.225
| CommandWebhookStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ComplianceStore.MessageExport |  Avg| 1ms| 2ms | 1ms | 88.630
| |  P99| 5ms| 9ms | 4ms | 80.808
| DraftStore.Delete |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 9ms| 8ms | -1ms | -10.800
| |  P99| 24ms| 24ms | 0s | 0.000
| DraftStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.GetDraftsForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Upsert |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| EmojiStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| EmojiStore.GetMultipleByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.AttachToPost |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 17ms| 15ms | -2ms | -11.453
| FileInfoStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.GetByIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| FileInfoStore.SetContent |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 17ms| 18ms | 1ms | 5.943
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| GroupStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| GroupStore.GetGroups |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| GroupStore.GetGroupsAssociatedToChannelsByTeam |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.GetAllByStatus |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.GetAllByTypePage |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.GetCountByStatusAndType |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.GetNewestJobByStatusesAndType |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 10ms| 5ms | -5ms | -50.761
| JobStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -10.791
| JobStore.UpdateOptimistically |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 13.899
| JobStore.UpdateStatus |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.UpdateStatusOptimistically |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 18ms | 9ms | 95.225
| LicenseStore.GetAll |  Avg| 1ms| 0s | -1ms | -135.234
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -45.940
| PluginStore.Delete |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PluginStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PluginStore.List |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PluginStore.SetWithOptions |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 21ms| 20ms | -1ms | -4.732
| PostAcknowledgementStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostAcknowledgementStore.GetForPosts |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.DeleteExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.GetSingle |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPriorityStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPriorityStore.GetForPosts |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 6ms | 0s | 0.000
| PostStore.Delete |  Avg| 14ms| 13ms | -1ms | -7.330
| |  P99| 25ms| 25ms | 0s | 0.000
| PostStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.GetEtag |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 6ms | -1ms | -14.565
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 7ms | 1ms | 17.216
| PostStore.GetPostIdBeforeTime |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostReminderMetadata |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostReminders |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| PostStore.GetPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| PostStore.GetPostsAfter |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostsBefore |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostsByThread |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostsSince |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 39ms| 39ms | 0s | 0.000
| PostStore.GetSingle |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 47ms| 48ms | 1ms | 2.110
| PostStore.SearchPostsForUser |  Avg| 58ms| 61ms | 3ms | 5.159
| |  P99| 535ms| 248ms | -287ms | -53.625
| PostStore.SetPostReminder |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.Update |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 25ms| 29ms | 4ms | 16.097
| PreferenceStore.DeleteCategoryAndName |  Avg| 2ms| 3ms | 1ms | 45.492
| |  P99| 5ms| 5ms | 0s | 0.000
| PreferenceStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PreferenceStore.GetAll |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 11.151
| PreferenceStore.Save |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 32ms| 35ms | 3ms | 9.515
| ProductNoticesStore.GetViews |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 33ms| 32ms | -1ms | -3.076
| |  P99| 88ms| 89ms | 1ms | 1.132
| ReactionStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| RetentionPolicyStore.GetAll |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| RetentionPolicyStore.GetCount |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| RoleStore.ChannelHigherScopedPermissions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| RoleStore.GetByNames |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetPendingScheduledPosts |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetScheduledPostsForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.UpdateOldScheduledPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 17ms| 17ms | 0s | 0.000
| SessionStore.GetLRUSessions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsExpired |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Remove |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 20ms| 20ms | 0s | 0.000
| SessionStore.UpdateLastActivityAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| SharedChannelStore.HasChannel |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.GetByIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.SaveOrUpdate |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| StatusStore.UpdateLastActivityAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 13.494
| SystemStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.029
| TeamStore.AnalyticsTeamCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetActiveMemberCount |  Avg| 100ms| 102ms | 2ms | 1.995
| |  P99| 248ms| 249ms | 1ms | 0.404
| TeamStore.GetAllPage |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 6ms | 0s | 0.000
| TeamStore.GetTeamsByUserId |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetTeamsForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetTotalMemberCount |  Avg| 77ms| 77ms | 0s | 0.000
| |  P99| 100ms| 100ms | 0s | 0.000
| TeamStore.SaveMember |  Avg| 68ms| 68ms | 0s | 0.000
| |  P99| 100ms| 100ms | 0s | 0.000
| ThreadStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetMembershipForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetTeamsUnreadForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| ThreadStore.GetThreadFollowers |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetThreadForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetThreadsForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetTotalThreads |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetTotalUnreadMentions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetTotalUnreadThreads |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.MaintainMembership |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 17ms| 17ms | 0s | 0.000
| ThreadStore.MarkAllAsReadByChannels |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.283
| ThreadStore.MarkAsRead |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 13.715
| ThreadStore.UpdateMembership |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| TokenStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AnalyticsActiveCount |  Avg| 150ms| 154ms | 4ms | 2.667
| |  P99| 249ms| 249ms | 0s | 0.000
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AutocompleteUsersInChannel |  Avg| 130ms| 130ms | 0s | 0.000
| |  P99| 369ms| 381ms | 12ms | 3.249
| UserStore.Count |  Avg| 48ms| 50ms | 2ms | 4.149
| |  P99| 99ms| 99ms | 0s | 0.000
| UserStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 6ms | 0s | 0.000
| UserStore.GetAllProfiles |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| UserStore.GetAllProfilesInChannel |  Avg| 188ms| 192ms | 4ms | 2.132
| |  P99| 495ms| 496ms | 1ms | 0.202
| UserStore.GetByUsername |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
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
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfilesNotInChannel |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetUnreadCount |  Avg| 4ms| 3ms | -1ms | -28.087
| |  P99| 8ms| 9ms | 1ms | 12.399
| UserStore.IsEmpty |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.Save |  Avg| 68ms| 68ms | 0s | 0.000
| |  P99| 100ms| 100ms | 0s | 0.000
| UserStore.Search |  Avg| 57ms| 58ms | 1ms | 1.750
| |  P99| 242ms| 243ms | 1ms | 0.413
| UserStore.Update |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| UserStore.UpdateFailedPasswordAttempts |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 18ms| 18ms | 0s | 0.000
| UserStore.UpdateLastLogin |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 15ms| 12ms | -3ms | -19.473
| UserStore.UpdateUpdateAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 17ms| 15ms | -2ms | -11.853
| UserTermsOfServiceStore.GetByUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| WebhookStore.GetOutgoingByTeam |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 12ms| 11ms | -1ms | -8.635
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 135ms| 133ms | -2ms | -1.478
| | P99| 248ms| 248ms | 0s | 0.000
| addTeamMember | Avg| 630ms| 632ms | 2ms | 0.317
| | P99| 997ms| 1.397s | 400ms | 40.100
| autocompleteChannelsForTeamForSearch | Avg| 296ms| 242ms | -54ms | -18.216
| | P99| 3.3s| 2.368s | -932ms | -28.238
| autocompleteUsers | Avg| 110ms| 113ms | 3ms | 2.728
| | P99| 323ms| 346ms | 23ms | 7.124
| createChannel | Avg| 159ms| 169ms | 10ms | 6.281
| | P99| 249ms| 248ms | -1ms | -0.402
| createChannelBookmark | Avg| 17ms| 17ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| createDirectChannel | Avg| 153ms| 135ms | -18ms | -11.793
| | P99| 248ms| 248ms | 0s | 0.000
| createGroupChannel | Avg| 217ms| 211ms | -6ms | -2.763
| | P99| 490ms| 483ms | -7ms | -1.429
| createPost | Avg| 151ms| 151ms | 0s | 0.000
| | P99| 822ms| 817ms | -5ms | -0.608
| createUser | Avg| 101ms| 100ms | -1ms | -0.993
| | P99| 246ms| 246ms | 0s | 0.000
| deleteDraft | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| deletePost | Avg| 19ms| 18ms | -1ms | -5.324
| | P99| 25ms| 25ms | 0s | 0.000
| followThreadByUser | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 24ms| 10ms | -14ms | -58.818
| getAllTeams | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 8ms| 7ms | -1ms | -12.982
| getAnalytics | Avg| 227ms| 213ms | -14ms | -6.165
| | P99| 248ms| 248ms | 0s | 0.000
| getCategoriesForTeamForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 13ms| 16ms | 3ms | 22.821
| getChannel | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getChannelMember | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 23ms| 22ms | -1ms | -4.360
| getChannelMembers | Avg| 2ms| 0s | -2ms | -111.187
| | P99| 5ms| 0s | -5ms | -101.010
| getChannelMembersForTeamForUser | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getChannelMembersForUser | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 24ms| 25ms | 1ms | 4.111
| getChannelStats | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 209ms| 209ms | 0s | 0.000
| getChannelUnread | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getChannelsForTeamForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 6ms| 6ms | 0s | 0.000
| getChannelsForUser | Avg| 5ms| 4ms | -1ms | -19.568
| | P99| 184ms| 189ms | 5ms | 2.718
| getClientConfig | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 23ms| 23ms | 0s | 0.000
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getDrafts | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getFilePreview | Avg| 36ms| 36ms | 0s | 0.000
| | P99| 93ms| 93ms | 0s | 0.000
| getFileThumbnail | Avg| 30ms| 30ms | 0s | 0.000
| | P99| 80ms| 80ms | 0s | 0.000
| getFilteredUsersStats | Avg| 38ms| 17ms | -21ms | -55.297
| | P99| 98ms| 25ms | -73ms | -74.490
| getGroups | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getGroupsAssociatedToChannelsByTeam | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getJobsByType | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getPostThread | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| getPostsForChannel | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 77ms| 74ms | -3ms | -3.916
| getPostsForChannelAroundLastUnread | Avg| 13ms| 13ms | 0s | 0.000
| | P99| 48ms| 48ms | 0s | 0.000
| getPreferences | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 9ms| 10ms | 1ms | 10.692
| getPrevTrialLicense | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getProductNotices | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getProfileImage | Avg| 85ms| 79ms | -6ms | -7.089
| | P99| 384ms| 334ms | -50ms | -13.020
| getPublicChannelsForTeam | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 11ms| 19ms | 8ms | 74.207
| getRolesByNames | Avg| 0s| 1ms | 1ms | 254.450
| | P99| 5ms| 5ms | 0s | 0.000
| getServerLimits | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 0s | -5ms | -101.010
| getTeamMember | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getTeamMembersForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 10ms| 9ms | -1ms | -10.514
| getTeamScheduledPosts | Avg| 2ms| 0s | -2ms | -129.374
| | P99| 5ms| 0s | -5ms | -101.010
| getTeamStats | Avg| 100ms| 102ms | 2ms | 1.993
| | P99| 248ms| 249ms | 1ms | 0.404
| getTeamsForUser | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getTeamsUnreadForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| getThreadsForUser | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUser | Avg| 1ms| 2ms | 1ms | 68.699
| | P99| 8ms| 8ms | 0s | 0.000
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsersByNames | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| listChannelBookmarksForChannel | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| login | Avg| 56ms| 55ms | -1ms | -1.789
| | P99| 241ms| 240ms | -1ms | -0.414
| logout | Avg| 19ms| 21ms | 2ms | 10.581
| | P99| 25ms| 49ms | 24ms | 96.579
| patchPost | Avg| 21ms| 21ms | 0s | 0.000
| | P99| 46ms| 40ms | -6ms | -13.067
| removeUserCustomStatus | Avg| 96ms| 81ms | -15ms | -15.580
| | P99| 246ms| 244ms | -2ms | -0.811
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 9ms| 9ms | 0s | 0.000
| searchAllChannels | Avg| 945ms| 957ms | 12ms | 1.270
| | P99| 2.459s| 2.46s | 1ms | 0.041
| searchGroupChannels | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| searchPostsInTeam | Avg| 62ms| 64ms | 2ms | 3.243
| | P99| 535ms| 399ms | -136ms | -25.411
| searchUsers | Avg| 58ms| 59ms | 1ms | 1.720
| | P99| 243ms| 243ms | 0s | 0.000
| setPostReminder | Avg| 11ms| 12ms | 1ms | 8.716
| | P99| 25ms| 25ms | 0s | 0.000
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 10ms| 9ms | -1ms | -10.462
| | P99| 24ms| 25ms | 1ms | 4.093
| updateCategoriesForTeamForUser | Avg| 47ms| 50ms | 3ms | 6.405
| | P99| 232ms| 233ms | 1ms | 0.431
| updatePreferences | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| updateReadStateThreadByUser | Avg| 14ms| 14ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 403ms| 386ms | -17ms | -4.223
| | P99| 987ms| 988ms | 1ms | 0.101
| upsertDraft | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| viewChannel | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
