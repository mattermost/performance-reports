### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostStore.AnalyticsPostCount | avg | 2ms | 364ms | 362ms | 15605.02
| UserStore.AnalyticsActiveCount | avg | 32ms | 155ms | 123ms | 381.39
| ChannelBookmarkStore.Save | avg | 7ms | 10ms | 3ms | 42.07
| ChannelStore.AutocompleteInTeamForSearch | avg | 276ms | 280ms | 4ms | 1.45
| ChannelStore.Autocomplete | avg | 936ms | 949ms | 13ms | 1.39
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostStore.AnalyticsPostCount | p99 | 5ms | 990ms | 985ms | 19891.73
| UserStore.AnalyticsActiveCount | p99 | 50ms | 249ms | 199ms | 399.87
| ClusterDiscoveryStore.SetLastPingAt | p99 | 5ms | 19ms | 14ms | 282.83
| UserStore.Update | p99 | 18ms | 40ms | 22ms | 121.53
| JobStore.GetNewestJobByStatusesAndType | p99 | 5ms | 10ms | 5ms | 101.01
| ChannelStore.AnalyticsTypeCount | p99 | 5ms | 10ms | 5ms | 100.95
| UserStore.GetByUsername | p99 | 5ms | 10ms | 5ms | 93.49
| ChannelStore.GetPinnedPostCount | p99 | 17ms | 32ms | 15ms | 88.76
| UserAccessTokenStore.GetByToken | p99 | 5ms | 9ms | 4ms | 80.81
| JobStore.UpdateStatusOptimistically | p99 | 5ms | 9ms | 4ms | 80.81
| FileInfoStore.AttachToPost | p99 | 9ms | 16ms | 7ms | 74.87
| PostStore.Update | p99 | 25ms | 43ms | 18ms | 73.08
| ThreadStore.GetThreadFollowers | p99 | 5ms | 8ms | 3ms | 60.01
| ChannelStore.CreateDirectChannel | p99 | 25ms | 38ms | 13ms | 52.31
| TeamStore.GetTeamsForUser | p99 | 9ms | 13ms | 4ms | 45.52
| FileInfoStore.Save | p99 | 6ms | 8ms | 2ms | 32.52
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 7ms | 9ms | 2ms | 26.94
| UserStore.UpdateLastLogin | p99 | 7ms | 9ms | 2ms | 26.71
| UserStore.GetUnreadCount | p99 | 12ms | 15ms | 3ms | 24.61
| ReactionStore.GetForPost | p99 | 8ms | 10ms | 2ms | 24.25
| ChannelStore.AutocompleteInTeamForSearch | p99 | 2.404s | 2.924s | 520ms | 21.63
| UserStore.UpdateUpdateAt | p99 | 10ms | 12ms | 2ms | 20.97
| AuditStore.Save | p99 | 16ms | 18ms | 2ms | 12.53
| SessionStore.Save | p99 | 18ms | 20ms | 2ms | 11.39
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| BotStore.GetAll | avg | 2ms | 0s | -2ms | -102.09
| PreferenceStore.DeleteCategoryAndName | avg | 3ms | 1ms | -2ms | -68.58
| PostStore.SetPostReminder | avg | 6ms | 3ms | -3ms | -48.73
| StatusStore.SaveOrUpdate | avg | 6ms | 3ms | -3ms | -46.58
| DraftStore.DeleteDraftsAssociatedWithPost | avg | 10ms | 8ms | -2ms | -19.92
| PostStore.Delete | avg | 11ms | 9ms | -2ms | -19.00
| ChannelMemberHistoryStore.GetUsersInChannelDuring | avg | 200ms | 166ms | -34ms | -17.04
| UserStore.Count | avg | 62ms | 52ms | -10ms | -16.25
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 15ms | 13ms | -2ms | -13.30
| ChannelStore.GetTeamChannels | avg | 24ms | 22ms | -2ms | -8.21
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| RetentionPolicyStore.GetCount | p99 | 5ms | 0s | -5ms | -101.01
| RetentionPolicyStore.GetAll | p99 | 5ms | 0s | -5ms | -101.01
| BotStore.GetAll | p99 | 5ms | 0s | -5ms | -101.01
| StatusStore.SaveOrUpdate | p99 | 161ms | 5ms | -156ms | -96.94
| PreferenceStore.DeleteCategoryAndName | p99 | 24ms | 5ms | -19ms | -78.35
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 136ms | 49ms | -87ms | -63.99
| UserStore.Count | p99 | 224ms | 99ms | -125ms | -55.68
| PostStore.SetPostReminder | p99 | 10ms | 5ms | -5ms | -50.38
| ChannelStore.GetTeamChannels | p99 | 49ms | 25ms | -24ms | -49.23
| PostPriorityStore.GetForPost | p99 | 9ms | 5ms | -4ms | -45.98
| ThreadStore.MarkAllAsReadByChannels | p99 | 9ms | 5ms | -4ms | -44.95
| JobStore.Save | p99 | 8ms | 5ms | -3ms | -38.96
| DraftStore.GetDraftsForUser | p99 | 7ms | 5ms | -2ms | -29.72
| ChannelStore.Get | p99 | 7ms | 5ms | -2ms | -29.01
| SessionStore.Get | p99 | 19ms | 16ms | -3ms | -16.06
| UserStore.AutocompleteUsersInChannel | p99 | 358ms | 341ms | -17ms | -4.74
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getChannelsForUser | avg | 8ms | 13ms | 5ms | 62.15
| createChannelBookmark | avg | 11ms | 14ms | 3ms | 27.61
| removeUserCustomStatus | avg | 85ms | 98ms | 13ms | 15.21
| updateCategoriesForTeamForUser | avg | 27ms | 29ms | 2ms | 7.47
| searchAllChannels | avg | 936ms | 949ms | 13ms | 1.39
| addChannelMember | avg | 145ms | 147ms | 2ms | 1.38
| createPost | avg | 146ms | 148ms | 2ms | 1.37
| autocompleteChannelsForTeamForSearch | avg | 277ms | 280ms | 3ms | 1.08
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| followThreadByUser | p99 | 10ms | 24ms | 14ms | 140.68
| logout | p99 | 25ms | 47ms | 22ms | 88.53
| getTeamMembersForUser | p99 | 12ms | 15ms | 3ms | 25.53
| autocompleteChannelsForTeamForSearch | p99 | 2.404s | 2.924s | 520ms | 21.63
| unfollowThreadByUser | p99 | 21ms | 24ms | 3ms | 14.02
| getChannelsForUser | p99 | 208ms | 219ms | 11ms | 5.29
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getRolesByNames | avg | 4ms | 1ms | -3ms | -79.54
| setPostReminder | avg | 16ms | 13ms | -3ms | -18.38
| deletePost | avg | 16ms | 14ms | -2ms | -12.37
| createGroupChannel | avg | 214ms | 192ms | -22ms | -10.27
| getProfileImage | avg | 75ms | 70ms | -5ms | -6.67
| createChannel | avg | 187ms | 177ms | -10ms | -5.35
| autocompleteUsers | avg | 110ms | 107ms | -3ms | -2.74
| uploadFileStream | avg | 336ms | 329ms | -7ms | -2.08
| createDirectChannel | avg | 147ms | 144ms | -3ms | -2.04
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getTeamStats | p99 | 242ms | 100ms | -142ms | -58.56
| getDrafts | p99 | 9ms | 7ms | -2ms | -22.08
| getPostsForChannel | p99 | 150ms | 125ms | -25ms | -16.67
| getUser | p99 | 13ms | 11ms | -2ms | -15.79
| getChannelMember | p99 | 23ms | 20ms | -3ms | -12.97
| autocompleteUsers | p99 | 318ms | 289ms | -29ms | -9.12
| addTeamMember | p99 | 2.025s | 1.936s | -89ms | -4.39
| createPost | p99 | 814ms | 789ms | -25ms | -3.07
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 16ms| 18ms | 2ms | 12.528
| BotStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| BotStore.GetAll |  Avg| 2ms| 0s | -2ms | -102.092
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelBookmarkStore.Save |  Avg| 7ms| 10ms | 3ms | 42.071
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelMemberHistoryStore.GetUsersInChannelDuring |  Avg| 200ms| 166ms | -34ms | -17.037
| |  P99| 249ms| 249ms | 0s | 0.000
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 2ms| 3ms | 1ms | 45.725
| |  P99| 7ms| 9ms | 2ms | 26.942
| ChannelStore.AnalyticsTypeCount |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 10ms | 5ms | 100.946
| ChannelStore.Autocomplete |  Avg| 936ms| 949ms | 13ms | 1.389
| |  P99| 2.458s| 2.459s | 1ms | 0.041
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 276ms| 280ms | 4ms | 1.447
| |  P99| 2.404s| 2.924s | 520ms | 21.627
| ChannelStore.CreateDirectChannel |  Avg| 16ms| 16ms | 0s | 0.000
| |  P99| 25ms| 38ms | 13ms | 52.314
| ChannelStore.CreateInitialSidebarCategories |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 37ms| 37ms | 0s | 0.000
| ChannelStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 5ms | -2ms | -29.012
| ChannelStore.GetAllChannelMembersForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 10.731
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 15ms| 13ms | -2ms | -13.302
| |  P99| 136ms| 49ms | -87ms | -63.985
| ChannelStore.GetByName |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 21ms | 0s | 0.000
| ChannelStore.GetByNameIncludeDeleted |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannelUnread |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannelsByUser |  Avg| 6ms| 7ms | 1ms | 15.766
| |  P99| 47ms| 48ms | 1ms | 2.111
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetFileCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 14.893
| ChannelStore.GetGuestCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ChannelStore.GetMember |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -15.857
| ChannelStore.GetMemberCount |  Avg| 62ms| 62ms | 0s | 0.000
| |  P99| 245ms| 245ms | 0s | 0.000
| ChannelStore.GetMemberForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMemberLastViewedAt |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| ChannelStore.GetMembersForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMembersForUserWithPagination |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 25ms| 24ms | -1ms | -4.073
| ChannelStore.GetPinnedPostCount |  Avg| 2ms| 3ms | 1ms | 40.382
| |  P99| 17ms| 32ms | 15ms | 88.756
| ChannelStore.GetPublicChannelsForTeam |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ChannelStore.GetSidebarCategory |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.178
| ChannelStore.GetTeamChannels |  Avg| 24ms| 22ms | -2ms | -8.211
| |  P99| 49ms| 25ms | -24ms | -49.225
| ChannelStore.IncrementMentionCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.IsReadOnlyChannel |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.Save |  Avg| 10ms| 11ms | 1ms | 9.636
| |  P99| 48ms| 48ms | 0s | 0.000
| ChannelStore.SaveMember |  Avg| 22ms| 22ms | 0s | 0.000
| |  P99| 49ms| 49ms | 0s | 0.000
| ChannelStore.SearchGroupChannels |  Avg| 3ms| 2ms | -1ms | -39.766
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.UpdateLastViewedAt |  Avg| 3ms| 4ms | 1ms | 29.648
| |  P99| 8ms| 9ms | 1ms | 12.036
| ChannelStore.UpdateSidebarCategories |  Avg| 17ms| 18ms | 1ms | 5.971
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 2ms| 3ms | 1ms | 43.497
| |  P99| 5ms| 19ms | 14ms | 282.828
| CommandWebhookStore.Cleanup |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ComplianceStore.MessageExport |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Delete |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 10ms| 8ms | -2ms | -19.916
| |  P99| 25ms| 24ms | -1ms | -4.061
| DraftStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.GetDraftsForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 7ms| 5ms | -2ms | -29.716
| DraftStore.Upsert |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| EmojiStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| EmojiStore.GetMultipleByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.AttachToPost |  Avg| 3ms| 4ms | 1ms | 29.156
| |  P99| 9ms| 16ms | 7ms | 74.866
| FileInfoStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.GetByIds |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.896
| FileInfoStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 6ms| 8ms | 2ms | 32.516
| FileInfoStore.SetContent |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -10.792
| GroupStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.196
| GroupStore.GetGroups |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| JobStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.GetAllByStatus |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.GetAllByTypePage |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.GetCountByStatusAndType |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 14.184
| JobStore.GetNewestJobByStatusesAndType |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 10ms | 5ms | 101.010
| JobStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 5ms | -3ms | -38.961
| JobStore.UpdateOptimistically |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.UpdateStatus |  Avg| 2ms| 3ms | 1ms | 41.018
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.UpdateStatusOptimistically |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.808
| LicenseStore.GetAll |  Avg| 2ms| 1ms | -1ms | -43.583
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Save |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PluginStore.Delete |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PluginStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PluginStore.List |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PluginStore.SetWithOptions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostAcknowledgementStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostAcknowledgementStore.GetForPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 19ms| 19ms | 0s | 0.000
| PostPersistentNotificationStore.DeleteExpired |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPriorityStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -45.980
| PostPriorityStore.GetForPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 19ms| 19ms | 0s | 0.000
| PostStore.AnalyticsPostCount |  Avg| 2ms| 364ms | 362ms | 15605.022
| |  P99| 5ms| 990ms | 985ms | 19891.727
| PostStore.Delete |  Avg| 11ms| 9ms | -2ms | -18.998
| |  P99| 24ms| 24ms | 0s | 0.000
| PostStore.Get |  Avg| 4ms| 5ms | 1ms | 22.360
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.GetEtag |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdBeforeTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostReminderMetadata |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostReminders |  Avg| 3ms| 4ms | 1ms | 34.020
| |  P99| 9ms| 10ms | 1ms | 10.929
| PostStore.GetPosts |  Avg| 4ms| 5ms | 1ms | 22.339
| |  P99| 22ms| 23ms | 1ms | 4.636
| PostStore.GetPostsAfter |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostsBefore |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 6ms| 6ms | 0s | 0.000
| PostStore.GetPostsByThread |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostsSince |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 40ms| 40ms | 0s | 0.000
| PostStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| PostStore.SearchPostsForUser |  Avg| 56ms| 56ms | 0s | 0.000
| |  P99| 424ms| 420ms | -4ms | -0.944
| PostStore.SetPostReminder |  Avg| 6ms| 3ms | -3ms | -48.734
| |  P99| 10ms| 5ms | -5ms | -50.378
| PostStore.Update |  Avg| 10ms| 11ms | 1ms | 9.728
| |  P99| 25ms| 43ms | 18ms | 73.085
| PreferenceStore.DeleteCategoryAndName |  Avg| 3ms| 1ms | -2ms | -68.581
| |  P99| 24ms| 5ms | -19ms | -78.350
| PreferenceStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PreferenceStore.GetAll |  Avg| 3ms| 4ms | 1ms | 29.818
| |  P99| 15ms| 16ms | 1ms | 6.515
| PreferenceStore.Save |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 21ms| 22ms | 1ms | 4.683
| ProductNoticesStore.View |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 50ms| 50ms | 0s | 0.000
| ReactionStore.GetForPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 10ms | 2ms | 24.253
| RetentionPolicyStore.GetAll |  Avg| 1ms| 0s | -1ms | -71.606
| |  P99| 5ms| 0s | -5ms | -101.010
| RetentionPolicyStore.GetCount |  Avg| 1ms| 0s | -1ms | -97.079
| |  P99| 5ms| 0s | -5ms | -101.010
| RoleStore.ChannelHigherScopedPermissions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| RoleStore.GetByNames |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetPendingScheduledPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetScheduledPostsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.UpdateOldScheduledPosts |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SchemeStore.GetAllPage |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 19ms| 16ms | -3ms | -16.064
| SessionStore.GetLRUSessions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 13.357
| SessionStore.GetSessionsExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Remove |  Avg| 2ms| 3ms | 1ms | 41.606
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 18ms| 20ms | 2ms | 11.386
| SessionStore.UpdateLastActivityAt |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SharedChannelStore.HasChannel |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| StatusStore.GetByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.SaveOrUpdate |  Avg| 6ms| 3ms | -3ms | -46.581
| |  P99| 161ms| 5ms | -156ms | -96.941
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 3ms| 4ms | 1ms | 30.452
| |  P99| 10ms| 10ms | 0s | 0.000
| StatusStore.UpdateLastActivityAt |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SystemStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.AnalyticsTeamCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetActiveMemberCount |  Avg| 99ms| 98ms | -1ms | -1.015
| |  P99| 100ms| 100ms | 0s | 0.000
| TeamStore.GetAllPage |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| TeamStore.GetMember |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -16.969
| TeamStore.GetTeamsByUserId |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 11ms| 10ms | -1ms | -9.047
| TeamStore.GetTeamsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 13ms | 4ms | 45.521
| TeamStore.GetTotalMemberCount |  Avg| 75ms| 76ms | 1ms | 1.330
| |  P99| 100ms| 100ms | 0s | 0.000
| TeamStore.SaveMember |  Avg| 65ms| 65ms | 0s | 0.000
| |  P99| 100ms| 100ms | 0s | 0.000
| ThreadStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetMembershipForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetTeamsUnreadForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 12ms| 11ms | -1ms | -8.135
| ThreadStore.GetThreadFollowers |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 8ms | 3ms | 60.010
| ThreadStore.GetThreadForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetThreadsForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetTotalThreads |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ThreadStore.GetTotalUnreadMentions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ThreadStore.GetTotalUnreadThreads |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 7ms | -1ms | -12.374
| ThreadStore.MaintainMembership |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 10.658
| ThreadStore.MarkAllAsReadByChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -44.945
| ThreadStore.MarkAsRead |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.UpdateMembership |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TokenStore.Cleanup |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.808
| UserStore.AnalyticsActiveCount |  Avg| 32ms| 155ms | 123ms | 381.386
| |  P99| 50ms| 249ms | 199ms | 399.873
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AutocompleteUsersInChannel |  Avg| 126ms| 125ms | -1ms | -0.795
| |  P99| 358ms| 341ms | -17ms | -4.743
| UserStore.Count |  Avg| 62ms| 52ms | -10ms | -16.249
| |  P99| 224ms| 99ms | -125ms | -55.683
| UserStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetAllProfiles |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.476
| UserStore.GetAllProfilesInChannel |  Avg| 193ms| 192ms | -1ms | -0.518
| |  P99| 496ms| 495ms | -1ms | -0.201
| UserStore.GetByUsername |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 10ms | 5ms | 93.485
| UserStore.GetForLogin |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| UserStore.GetMany |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfileByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfilesByUsernames |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfilesInChannel |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfilesNotInChannel |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetUnreadCount |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 12ms| 15ms | 3ms | 24.606
| UserStore.IsEmpty |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.Save |  Avg| 69ms| 68ms | -1ms | -1.452
| |  P99| 100ms| 100ms | 0s | 0.000
| UserStore.Search |  Avg| 56ms| 56ms | 0s | 0.000
| |  P99| 240ms| 239ms | -1ms | -0.416
| UserStore.Update |  Avg| 4ms| 5ms | 1ms | 26.752
| |  P99| 18ms| 40ms | 22ms | 121.533
| UserStore.UpdateFailedPasswordAttempts |  Avg| 2ms| 3ms | 1ms | 40.201
| |  P99| 9ms| 10ms | 1ms | 10.854
| UserStore.UpdateLastLogin |  Avg| 2ms| 3ms | 1ms | 41.313
| |  P99| 7ms| 9ms | 2ms | 26.714
| UserStore.UpdateUpdateAt |  Avg| 2ms| 3ms | 1ms | 40.406
| |  P99| 10ms| 12ms | 2ms | 20.971
| UserTermsOfServiceStore.GetByUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -10.884
| WebhookStore.GetOutgoingByTeam |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 15ms| 14ms | -1ms | -6.652
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 145ms| 147ms | 2ms | 1.384
| | P99| 248ms| 248ms | 0s | 0.000
| addTeamMember | Avg| 627ms| 625ms | -2ms | -0.319
| | P99| 2.025s| 1.936s | -89ms | -4.394
| autocompleteChannelsForTeamForSearch | Avg| 277ms| 280ms | 3ms | 1.085
| | P99| 2.404s| 2.924s | 520ms | 21.627
| autocompleteUsers | Avg| 110ms| 107ms | -3ms | -2.738
| | P99| 318ms| 289ms | -29ms | -9.124
| createChannel | Avg| 187ms| 177ms | -10ms | -5.353
| | P99| 249ms| 249ms | 0s | 0.000
| createChannelBookmark | Avg| 11ms| 14ms | 3ms | 27.606
| | P99| 25ms| 25ms | 0s | 0.000
| createDirectChannel | Avg| 147ms| 144ms | -3ms | -2.039
| | P99| 248ms| 248ms | 0s | 0.000
| createGroupChannel | Avg| 214ms| 192ms | -22ms | -10.268
| | P99| 491ms| 488ms | -3ms | -0.611
| createPost | Avg| 146ms| 148ms | 2ms | 1.370
| | P99| 814ms| 789ms | -25ms | -3.071
| createUser | Avg| 102ms| 101ms | -1ms | -0.978
| | P99| 246ms| 246ms | 0s | 0.000
| deleteDraft | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 7ms| 6ms | -1ms | -15.283
| deletePost | Avg| 16ms| 14ms | -2ms | -12.371
| | P99| 25ms| 25ms | 0s | 0.000
| followThreadByUser | Avg| 8ms| 9ms | 1ms | 12.097
| | P99| 10ms| 24ms | 14ms | 140.676
| getAllTeams | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 12ms| 12ms | 0s | 0.000
| getCategoriesForTeamForUser | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 24ms| 24ms | 0s | 0.000
| getChannel | Avg| 5ms| 4ms | -1ms | -21.428
| | P99| 10ms| 9ms | -1ms | -10.006
| getChannelMember | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 23ms| 20ms | -3ms | -12.972
| getChannelMembersForTeamForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| getChannelStats | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 207ms| 206ms | -1ms | -0.483
| getChannelUnread | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getChannelsForTeamForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| getChannelsForUser | Avg| 8ms| 13ms | 5ms | 62.147
| | P99| 208ms| 219ms | 11ms | 5.289
| getClientConfig | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 15ms| 14ms | -1ms | -6.526
| getDrafts | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 9ms| 7ms | -2ms | -22.079
| getFilePreview | Avg| 37ms| 37ms | 0s | 0.000
| | P99| 92ms| 92ms | 0s | 0.000
| getFileThumbnail | Avg| 31ms| 31ms | 0s | 0.000
| | P99| 84ms| 83ms | -1ms | -1.197
| getJobsByType | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getPostThread | Avg| 12ms| 12ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| getPostsForChannel | Avg| 19ms| 18ms | -1ms | -5.144
| | P99| 150ms| 125ms | -25ms | -16.668
| getPostsForChannelAroundLastUnread | Avg| 18ms| 18ms | 0s | 0.000
| | P99| 51ms| 50ms | -1ms | -1.946
| getPreferences | Avg| 3ms| 4ms | 1ms | 28.917
| | P99| 16ms| 16ms | 0s | 0.000
| getPrevTrialLicense | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getProfileImage | Avg| 75ms| 70ms | -5ms | -6.670
| | P99| 249ms| 248ms | -1ms | -0.401
| getPublicChannelsForTeam | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| getRolesByNames | Avg| 4ms| 1ms | -3ms | -79.540
| | P99| 5ms| 5ms | 0s | 0.000
| getTeamMember | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getTeamMembersForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 12ms| 15ms | 3ms | 25.532
| getTeamStats | Avg| 99ms| 98ms | -1ms | -1.010
| | P99| 242ms| 100ms | -142ms | -58.558
| getTeamsForUser | Avg| 3ms| 2ms | -1ms | -39.924
| | P99| 11ms| 10ms | -1ms | -9.256
| getTeamsUnreadForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 19ms| 19ms | 0s | 0.000
| getThreadsForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 7ms| 7ms | 0s | 0.000
| getUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 13ms| 11ms | -2ms | -15.788
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 12ms| 11ms | -1ms | -8.303
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsersByNames | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| listChannelBookmarksForChannel | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 8ms| 7ms | -1ms | -13.196
| login | Avg| 52ms| 53ms | 1ms | 1.917
| | P99| 236ms| 238ms | 2ms | 0.846
| logout | Avg| 18ms| 19ms | 1ms | 5.667
| | P99| 25ms| 47ms | 22ms | 88.531
| patchPost | Avg| 24ms| 25ms | 1ms | 4.101
| | P99| 49ms| 49ms | 0s | 0.000
| removeUserCustomStatus | Avg| 85ms| 98ms | 13ms | 15.209
| | P99| 246ms| 246ms | 0s | 0.000
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 22ms| 22ms | 0s | 0.000
| searchAllChannels | Avg| 936ms| 949ms | 13ms | 1.389
| | P99| 2.458s| 2.459s | 1ms | 0.041
| searchGroupChannels | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| searchPostsInTeam | Avg| 61ms| 62ms | 1ms | 1.632
| | P99| 449ms| 451ms | 2ms | 0.445
| searchUsers | Avg| 57ms| 57ms | 0s | 0.000
| | P99| 241ms| 240ms | -1ms | -0.415
| setPostReminder | Avg| 16ms| 13ms | -3ms | -18.384
| | P99| 25ms| 25ms | 0s | 0.000
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 21ms| 24ms | 3ms | 14.018
| updateCategoriesForTeamForUser | Avg| 27ms| 29ms | 2ms | 7.472
| | P99| 50ms| 50ms | 0s | 0.000
| updatePreferences | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| updateReadStateThreadByUser | Avg| 23ms| 23ms | 0s | 0.000
| | P99| 49ms| 48ms | -1ms | -2.053
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 336ms| 329ms | -7ms | -2.085
| | P99| 961ms| 956ms | -5ms | -0.520
| upsertDraft | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 9ms| 10ms | 1ms | 10.667
| viewChannel | Avg| 10ms| 11ms | 1ms | 9.554
| | P99| 25ms| 25ms | 0s | 0.000
