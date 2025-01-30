### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| UserStore.GetProfilesInChannel | avg | 19ms | 55ms | 36ms | 189.95
| PreferenceStore.DeleteCategoryAndName | avg | 2ms | 5ms | 3ms | 121.30
| DraftStore.DeleteDraftsAssociatedWithPost | avg | 4ms | 8ms | 4ms | 92.49
| PostStore.AnalyticsPostCount | avg | 130ms | 236ms | 106ms | 81.69
| PostStore.SearchPostsForUser | avg | 19ms | 28ms | 9ms | 46.74
| ChannelStore.AutocompleteInTeamForSearch | avg | 19ms | 27ms | 8ms | 41.50
| TeamStore.GetTotalMemberCount | avg | 31ms | 33ms | 2ms | 6.41
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PreferenceStore.DeleteCategoryAndName | p99 | 10ms | 46ms | 36ms | 378.94
| DraftStore.DeleteDraftsAssociatedWithPost | p99 | 10ms | 46ms | 36ms | 366.10
| ChannelBookmarkStore.Delete | p99 | 10ms | 25ms | 15ms | 150.75
| PostStore.SearchPostsForUser | p99 | 331ms | 753ms | 422ms | 127.64
| JobStore.UpdateStatusOptimistically | p99 | 8ms | 14ms | 6ms | 71.86
| PostStore.Update | p99 | 25ms | 37ms | 12ms | 48.08
| ChannelStore.GetSidebarCategory | p99 | 25ms | 35ms | 10ms | 40.67
| PreferenceStore.GetAll | p99 | 5ms | 7ms | 2ms | 39.93
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 9ms | 11ms | 2ms | 21.56
| SessionStore.Save | p99 | 12ms | 14ms | 2ms | 16.01
| PluginStore.SetWithOptions | p99 | 14ms | 16ms | 2ms | 13.86
| ChannelStore.GetByName | p99 | 18ms | 20ms | 2ms | 11.36
| UserStore.GetAllProfilesInChannel | p99 | 350ms | 377ms | 27ms | 7.72
| ChannelStore.CreateInitialSidebarCategories | p99 | 45ms | 48ms | 3ms | 6.60
| UserStore.GetProfilesInChannel | p99 | 234ms | 247ms | 13ms | 5.55
| ChannelStore.AutocompleteInTeamForSearch | p99 | 93ms | 97ms | 4ms | 4.29
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.GetMemberCountsByGroup | avg | 4ms | 0s | -4ms | -113.07
| ChannelStore.CreateSidebarCategory | avg | 25ms | 0s | -25ms | -98.23
| ChannelStore.GetMembers | avg | 2ms | 0s | -2ms | -90.78
| StatusStore.SaveOrUpdate | avg | 16ms | 4ms | -12ms | -73.11
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.GetMemberCountsByGroup | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.GetMembers | p99 | 5ms | 0s | -5ms | -101.01
| RetentionPolicyStore.GetAll | p99 | 5ms | 0s | -5ms | -101.01
| RetentionPolicyStore.GetCount | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.CreateSidebarCategory | p99 | 50ms | 0s | -50ms | -100.76
| StatusStore.SaveOrUpdate | p99 | 288ms | 9ms | -279ms | -96.75
| PostPersistentNotificationStore.Get | p99 | 19ms | 5ms | -14ms | -74.87
| JobStore.GetCountByStatusAndType | p99 | 19ms | 6ms | -13ms | -68.42
| UserStore.Count | p99 | 22ms | 10ms | -12ms | -54.55
| ChannelStore.GetTeamChannels | p99 | 45ms | 25ms | -20ms | -44.20
| ChannelStore.UpdateSidebarCategories | p99 | 84ms | 50ms | -34ms | -40.72
| RoleStore.GetByNames | p99 | 8ms | 5ms | -3ms | -38.46
| ChannelStore.CreateDirectChannel | p99 | 39ms | 25ms | -14ms | -35.56
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 93ms | 65ms | -28ms | -30.22
| ThreadStore.MarkAllAsReadByChannels | p99 | 7ms | 5ms | -2ms | -29.54
| ClusterDiscoveryStore.SetLastPingAt | p99 | 12ms | 9ms | -3ms | -24.80
| FileInfoStore.SetContent | p99 | 21ms | 17ms | -4ms | -18.96
| ChannelStore.Save | p99 | 26ms | 24ms | -2ms | -7.69
| UserStore.AutocompleteUsersInChannel | p99 | 170ms | 161ms | -9ms | -5.30
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| autocompleteChannelsForTeamForSearch | avg | 19ms | 27ms | 8ms | 41.38
| searchPostsInTeam | avg | 24ms | 34ms | 10ms | 41.17
| setPostReminder | avg | 14ms | 17ms | 3ms | 21.02
| createDirectChannel | avg | 144ms | 172ms | 28ms | 19.38
| createGroupChannel | avg | 226ms | 252ms | 26ms | 11.51
| createChannel | avg | 172ms | 191ms | 19ms | 11.06
| addChannelMember | avg | 144ms | 158ms | 14ms | 9.73
| createUser | avg | 123ms | 127ms | 4ms | 3.25
| login | avg | 63ms | 65ms | 2ms | 3.15
| addTeamMember | avg | 478ms | 487ms | 9ms | 1.88
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| searchPostsInTeam | p99 | 331ms | 753ms | 422ms | 127.64
| setPostReminder | p99 | 25ms | 47ms | 22ms | 88.53
| unfollowThreadByUser | p99 | 25ms | 40ms | 15ms | 60.37
| createDirectChannel | p99 | 304ms | 476ms | 172ms | 56.63
| createUser | p99 | 285ms | 382ms | 97ms | 34.03
| getChannel | p99 | 9ms | 11ms | 2ms | 23.32
| patchPost | p99 | 41ms | 46ms | 5ms | 12.05
| getPostsForChannelAroundLastUnread | p99 | 36ms | 38ms | 2ms | 5.49
| autocompleteChannelsForTeamForSearch | p99 | 93ms | 97ms | 4ms | 4.29
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getChannelMembers | avg | 3ms | 0s | -3ms | -119.04
| channelMemberCountsByGroup | avg | 4ms | 0s | -4ms | -109.41
| createCategoryForTeamForUser | avg | 27ms | 0s | -27ms | -100.87
| getUserByUsername | avg | 2ms | 0s | -2ms | -81.46
| getRolesByNames | avg | 4ms | 2ms | -2ms | -54.00
| getProfileImage | avg | 75ms | 67ms | -8ms | -10.67
| removeUserCustomStatus | avg | 103ms | 98ms | -5ms | -4.84
| uploadFileStream | avg | 340ms | 336ms | -4ms | -1.18
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| channelMemberCountsByGroup | p99 | 5ms | 0s | -5ms | -101.01
| getUserByUsername | p99 | 5ms | 0s | -5ms | -101.01
| getChannelMembers | p99 | 5ms | 0s | -5ms | -101.01
| getClientLicense | p99 | 5ms | 0s | -5ms | -101.01
| createCategoryForTeamForUser | p99 | 50ms | 0s | -50ms | -100.50
| logout | p99 | 48ms | 25ms | -23ms | -47.55
| autocompleteUsers | p99 | 145ms | 136ms | -9ms | -6.20
| addChannelMember | p99 | 443ms | 425ms | -18ms | -4.07
| uploadFileStream | p99 | 969ms | 956ms | -13ms | -1.34
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 16ms| 16ms | 0s | 0.000
| BotStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| BotStore.GetAll |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelBookmarkStore.Delete |  Avg| 6ms| 7ms | 1ms | 17.669
| |  P99| 10ms| 25ms | 15ms | 150.754
| ChannelBookmarkStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelBookmarkStore.Save |  Avg| 11ms| 10ms | -1ms | -9.005
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 11ms | 2ms | 21.565
| ChannelStore.AnalyticsTypeCount |  Avg| 2ms| 1ms | -1ms | -63.895
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.Autocomplete |  Avg| 31ms| 32ms | 1ms | 3.258
| |  P99| 98ms| 98ms | 0s | 0.000
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 19ms| 27ms | 8ms | 41.503
| |  P99| 93ms| 97ms | 4ms | 4.290
| ChannelStore.CreateDirectChannel |  Avg| 18ms| 18ms | 0s | 0.000
| |  P99| 39ms| 25ms | -14ms | -35.555
| ChannelStore.CreateInitialSidebarCategories |  Avg| 20ms| 20ms | 0s | 0.000
| |  P99| 45ms| 48ms | 3ms | 6.600
| ChannelStore.CreateSidebarCategory |  Avg| 25ms| 0s | -25ms | -98.226
| |  P99| 50ms| 0s | -50ms | -100.756
| ChannelStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetAllChannelMembersForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 12ms| 11ms | -1ms | -8.425
| |  P99| 93ms| 65ms | -28ms | -30.224
| ChannelStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 18ms| 20ms | 2ms | 11.355
| ChannelStore.GetByNameIncludeDeleted |  Avg| 1ms| 2ms | 1ms | 108.730
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannelUnread |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannels |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannelsByUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetFileCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetGuestCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 6ms | 1ms | 20.003
| ChannelStore.GetMember |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ChannelStore.GetMemberCount |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.GetMemberCountsByGroup |  Avg| 4ms| 0s | -4ms | -113.067
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelStore.GetMemberForPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.194
| ChannelStore.GetMemberLastViewedAt |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMembers |  Avg| 2ms| 0s | -2ms | -90.782
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelStore.GetMembersForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMembersForUserWithPagination |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ChannelStore.GetPinnedPostCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetPublicChannelsForTeam |  Avg| 11ms| 12ms | 1ms | 8.744
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 9ms| 10ms | 1ms | 10.767
| |  P99| 24ms| 25ms | 1ms | 4.087
| ChannelStore.GetSidebarCategory |  Avg| 8ms| 9ms | 1ms | 12.004
| |  P99| 25ms| 35ms | 10ms | 40.671
| ChannelStore.GetTeamChannels |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 45ms| 25ms | -20ms | -44.199
| ChannelStore.IncrementMentionCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ChannelStore.IsReadOnlyChannel |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.Save |  Avg| 11ms| 10ms | -1ms | -9.103
| |  P99| 26ms| 24ms | -2ms | -7.693
| ChannelStore.SaveMember |  Avg| 22ms| 22ms | 0s | 0.000
| |  P99| 49ms| 49ms | 0s | 0.000
| ChannelStore.SearchGroupChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ChannelStore.UpdateLastViewedAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ChannelStore.UpdateSidebarCategories |  Avg| 41ms| 41ms | 0s | 0.000
| |  P99| 84ms| 50ms | -34ms | -40.718
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 4ms| 3ms | -1ms | -27.821
| |  P99| 12ms| 9ms | -3ms | -24.795
| CommandWebhookStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Delete |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 6ms| 7ms | 1ms | 16.449
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 4ms| 8ms | 4ms | 92.486
| |  P99| 10ms| 46ms | 36ms | 366.100
| DraftStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.GetDraftsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Upsert |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| EmojiStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| EmojiStore.GetMultipleByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.AttachToPost |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 18ms| 17ms | -1ms | -5.502
| FileInfoStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.GetByIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.Save |  Avg| 5ms| 4ms | -1ms | -22.086
| |  P99| 9ms| 10ms | 1ms | 10.543
| FileInfoStore.SetContent |  Avg| 8ms| 7ms | -1ms | -13.318
| |  P99| 21ms| 17ms | -4ms | -18.957
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| GroupStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| GroupStore.GetGroups |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| GroupStore.GetGroupsAssociatedToChannelsByTeam |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 6ms | 1ms | 20.202
| JobStore.GetAllByStatus |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 7ms | -1ms | -12.552
| JobStore.GetAllByTypePage |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.GetCountByStatusAndType |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 19ms| 6ms | -13ms | -68.421
| JobStore.GetNewestJobByStatusesAndType |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| JobStore.UpdateOptimistically |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| JobStore.UpdateStatus |  Avg| 3ms| 4ms | 1ms | 29.280
| |  P99| 7ms| 6ms | -1ms | -14.925
| JobStore.UpdateStatusOptimistically |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 8ms| 14ms | 6ms | 71.856
| LicenseStore.GetAll |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 13.334
| PluginStore.Delete |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 7ms | 1ms | 15.958
| PluginStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PluginStore.List |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PluginStore.SetWithOptions |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 14ms| 16ms | 2ms | 13.858
| PostAcknowledgementStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostAcknowledgementStore.GetForPosts |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 7ms | 1ms | 15.624
| PostPersistentNotificationStore.DeleteExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 5ms | -14ms | -74.866
| PostPersistentNotificationStore.GetSingle |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPriorityStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPriorityStore.GetForPosts |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| PostStore.AnalyticsPostCount |  Avg| 130ms| 236ms | 106ms | 81.694
| |  P99| 495ms| 496ms | 1ms | 0.202
| PostStore.Delete |  Avg| 14ms| 15ms | 1ms | 7.063
| |  P99| 25ms| 25ms | 0s | 0.000
| PostStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.GetEtag |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 6ms | 1ms | 18.851
| PostStore.GetPostIdBeforeTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostReminderMetadata |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostReminders |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 24ms| 23ms | -1ms | -4.211
| PostStore.GetPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 10.956
| PostStore.GetPostsAfter |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostsBefore |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| PostStore.GetPostsByThread |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.GetPostsSince |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 38ms| 39ms | 1ms | 2.615
| PostStore.GetSingle |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 48ms| 48ms | 0s | 0.000
| PostStore.SearchPostsForUser |  Avg| 19ms| 28ms | 9ms | 46.744
| |  P99| 331ms| 753ms | 422ms | 127.637
| PostStore.SetPostReminder |  Avg| 7ms| 8ms | 1ms | 13.460
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.Update |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 25ms| 37ms | 12ms | 48.079
| PreferenceStore.DeleteCategoryAndName |  Avg| 2ms| 5ms | 3ms | 121.304
| |  P99| 10ms| 46ms | 36ms | 378.944
| PreferenceStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 6ms | 0s | 0.000
| PreferenceStore.GetAll |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 7ms | 2ms | 39.927
| PreferenceStore.Save |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ProductNoticesStore.ClearOldNotices |  Avg| 11ms| 12ms | 1ms | 8.782
| |  P99| 25ms| 25ms | 0s | 0.000
| ProductNoticesStore.GetViews |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 32ms| 33ms | 1ms | 3.110
| |  P99| 92ms| 93ms | 1ms | 1.085
| ReactionStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 7ms | -1ms | -12.896
| RetentionPolicyStore.GetAll |  Avg| 1ms| 0s | -1ms | -99.528
| |  P99| 5ms| 0s | -5ms | -101.010
| RetentionPolicyStore.GetCount |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 0s | -5ms | -101.010
| RoleStore.ChannelHigherScopedPermissions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| RoleStore.GetByNames |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 5ms | -3ms | -38.462
| ScheduledPostStore.GetPendingScheduledPosts |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetScheduledPostsForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.UpdateOldScheduledPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SchemeStore.GetAllPage |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 13ms| 13ms | 0s | 0.000
| SessionStore.GetLRUSessions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsExpired |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 7ms | -1ms | -12.848
| SessionStore.Remove |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 12ms| 14ms | 2ms | 16.013
| SessionStore.UpdateLastActivityAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| SharedChannelStore.HasChannel |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.GetByIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.SaveOrUpdate |  Avg| 16ms| 4ms | -12ms | -73.107
| |  P99| 288ms| 9ms | -279ms | -96.745
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.UpdateLastActivityAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| SystemStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.AnalyticsTeamCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetActiveMemberCount |  Avg| 34ms| 33ms | -1ms | -2.976
| |  P99| 50ms| 50ms | 0s | 0.000
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
| TeamStore.GetTotalMemberCount |  Avg| 31ms| 33ms | 2ms | 6.411
| |  P99| 50ms| 50ms | 0s | 0.000
| TeamStore.SaveMember |  Avg| 22ms| 23ms | 1ms | 4.498
| |  P99| 47ms| 48ms | 1ms | 2.136
| ThreadStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetMembershipForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetTeamsUnreadForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetThreadFollowers |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetThreadForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 16ms| 16ms | 0s | 0.000
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 16ms| 16ms | 0s | 0.000
| ThreadStore.GetThreadsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 7ms | 1ms | 17.404
| ThreadStore.GetTotalThreads |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetTotalUnreadMentions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 7ms | -1ms | -13.287
| ThreadStore.GetTotalUnreadThreads |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.MaintainMembership |  Avg| 6ms| 7ms | 1ms | 15.403
| |  P99| 19ms| 19ms | 0s | 0.000
| ThreadStore.MarkAllAsReadByChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 5ms | -2ms | -29.536
| ThreadStore.MarkAllAsReadByTeam |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.MarkAsRead |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.734
| ThreadStore.UpdateMembership |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| TokenStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AnalyticsActiveCount |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AutocompleteUsersInChannel |  Avg| 34ms| 34ms | 0s | 0.000
| |  P99| 170ms| 161ms | -9ms | -5.301
| UserStore.Count |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 22ms| 10ms | -12ms | -54.545
| UserStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetAllProfiles |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetAllProfilesInChannel |  Avg| 131ms| 132ms | 1ms | 0.764
| |  P99| 350ms| 377ms | 27ms | 7.718
| UserStore.GetByUsername |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetForLogin |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetMany |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfileByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfilesByUsernames |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfilesInChannel |  Avg| 19ms| 55ms | 36ms | 189.951
| |  P99| 234ms| 247ms | 13ms | 5.550
| UserStore.GetProfilesNotInChannel |  Avg| 3ms| 4ms | 1ms | 29.254
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetUnreadCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 14.741
| UserStore.IsEmpty |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.Save |  Avg| 67ms| 67ms | 0s | 0.000
| |  P99| 100ms| 100ms | 0s | 0.000
| UserStore.Search |  Avg| 25ms| 25ms | 0s | 0.000
| |  P99| 49ms| 49ms | 0s | 0.000
| UserStore.Update |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| UserStore.UpdateFailedPasswordAttempts |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 11ms| 12ms | 1ms | 9.089
| UserStore.UpdateLastLogin |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| UserStore.UpdateUpdateAt |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 12ms| 13ms | 1ms | 8.525
| UserTermsOfServiceStore.GetByUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| WebhookStore.GetOutgoingByTeam |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 23ms | 1ms | 4.588
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 144ms| 158ms | 14ms | 9.730
| | P99| 443ms| 425ms | -18ms | -4.068
| addTeamMember | Avg| 478ms| 487ms | 9ms | 1.885
| | P99| 988ms| 989ms | 1ms | 0.101
| autocompleteChannelsForTeamForSearch | Avg| 19ms| 27ms | 8ms | 41.376
| | P99| 93ms| 97ms | 4ms | 4.290
| autocompleteUsers | Avg| 31ms| 31ms | 0s | 0.000
| | P99| 145ms| 136ms | -9ms | -6.201
| channelMemberCountsByGroup | Avg| 4ms| 0s | -4ms | -109.406
| | P99| 5ms| 0s | -5ms | -101.010
| createCategoryForTeamForUser | Avg| 27ms| 0s | -27ms | -100.868
| | P99| 50ms| 0s | -50ms | -100.503
| createChannel | Avg| 172ms| 191ms | 19ms | 11.060
| | P99| 249ms| 249ms | 0s | 0.000
| createChannelBookmark | Avg| 17ms| 18ms | 1ms | 5.788
| | P99| 25ms| 25ms | 0s | 0.000
| createDirectChannel | Avg| 144ms| 172ms | 28ms | 19.380
| | P99| 304ms| 476ms | 172ms | 56.626
| createGroupChannel | Avg| 226ms| 252ms | 26ms | 11.509
| | P99| 494ms| 495ms | 1ms | 0.202
| createPost | Avg| 167ms| 166ms | -1ms | -0.597
| | P99| 489ms| 490ms | 1ms | 0.205
| createUser | Avg| 123ms| 127ms | 4ms | 3.255
| | P99| 285ms| 382ms | 97ms | 34.031
| deleteDraft | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| deletePost | Avg| 20ms| 20ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| followThreadByUser | Avg| 11ms| 12ms | 1ms | 8.699
| | P99| 25ms| 25ms | 0s | 0.000
| getAllTeams | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 8ms| 8ms | 0s | 0.000
| getCategoriesForTeamForUser | Avg| 9ms| 10ms | 1ms | 10.650
| | P99| 25ms| 25ms | 0s | 0.000
| getChannel | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 9ms| 11ms | 2ms | 23.323
| getChannelMember | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 19ms| 18ms | -1ms | -5.378
| getChannelMembers | Avg| 3ms| 0s | -3ms | -119.042
| | P99| 5ms| 0s | -5ms | -101.010
| getChannelMembersForTeamForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 8ms| 9ms | 1ms | 12.070
| getChannelStats | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 24ms| 24ms | 0s | 0.000
| getChannelUnread | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getChannelsForTeamForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 7ms| 8ms | 1ms | 14.053
| getChannelsForUser | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getClientConfig | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 21ms| 21ms | 0s | 0.000
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 0s | -5ms | -101.010
| getDrafts | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getFilePreview | Avg| 36ms| 36ms | 0s | 0.000
| | P99| 92ms| 92ms | 0s | 0.000
| getFileThumbnail | Avg| 30ms| 30ms | 0s | 0.000
| | P99| 83ms| 83ms | 0s | 0.000
| getJobsByType | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getPostThread | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 15ms| 14ms | -1ms | -6.558
| getPostsForChannel | Avg| 13ms| 13ms | 0s | 0.000
| | P99| 87ms| 88ms | 1ms | 1.154
| getPostsForChannelAroundLastUnread | Avg| 12ms| 12ms | 0s | 0.000
| | P99| 36ms| 38ms | 2ms | 5.489
| getPreferences | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 7ms| 8ms | 1ms | 14.745
| getPrevTrialLicense | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getProfileImage | Avg| 75ms| 67ms | -8ms | -10.673
| | P99| 250ms| 248ms | -2ms | -0.800
| getPublicChannelsForTeam | Avg| 12ms| 12ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| getRolesByNames | Avg| 4ms| 2ms | -2ms | -54.001
| | P99| 5ms| 5ms | 0s | 0.000
| getTeamMember | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getTeamMembersForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 8ms| 9ms | 1ms | 12.020
| getTeamStats | Avg| 34ms| 33ms | -1ms | -2.964
| | P99| 50ms| 50ms | 0s | 0.000
| getTeamsForUser | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getTeamsUnreadForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 9ms| 9ms | 0s | 0.000
| getThreadsForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 6ms| 7ms | 1ms | 15.487
| getUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 6ms| 7ms | 1ms | 16.265
| getUserByUsername | Avg| 2ms| 0s | -2ms | -81.463
| | P99| 5ms| 0s | -5ms | -101.010
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsersByNames | Avg| 1ms| 2ms | 1ms | 66.892
| | P99| 5ms| 5ms | 0s | 0.000
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| listChannelBookmarksForChannel | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| login | Avg| 63ms| 65ms | 2ms | 3.152
| | P99| 236ms| 237ms | 1ms | 0.423
| logout | Avg| 22ms| 23ms | 1ms | 4.494
| | P99| 48ms| 25ms | -23ms | -47.545
| patchPost | Avg| 20ms| 21ms | 1ms | 4.892
| | P99| 41ms| 46ms | 5ms | 12.048
| removeUserCustomStatus | Avg| 103ms| 98ms | -5ms | -4.842
| | P99| 247ms| 247ms | 0s | 0.000
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 18ms| 19ms | 1ms | 5.644
| searchAllChannels | Avg| 31ms| 32ms | 1ms | 3.238
| | P99| 98ms| 98ms | 0s | 0.000
| searchGroupChannels | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 9ms| 10ms | 1ms | 11.286
| searchPostsInTeam | Avg| 24ms| 34ms | 10ms | 41.169
| | P99| 331ms| 753ms | 422ms | 127.637
| searchUsers | Avg| 26ms| 26ms | 0s | 0.000
| | P99| 50ms| 50ms | 0s | 0.000
| setPostReminder | Avg| 14ms| 17ms | 3ms | 21.023
| | P99| 25ms| 47ms | 22ms | 88.531
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 12ms| 12ms | 0s | 0.000
| | P99| 25ms| 40ms | 15ms | 60.372
| updateCategoriesForTeamForUser | Avg| 59ms| 60ms | 1ms | 1.694
| | P99| 99ms| 99ms | 0s | 0.000
| updatePreferences | Avg| 10ms| 9ms | -1ms | -10.503
| | P99| 24ms| 24ms | 0s | 0.000
| updateReadStateAllThreadsByUser | Avg| 3ms| 4ms | 1ms | 32.548
| | P99| 5ms| 5ms | 0s | 0.000
| updateReadStateThreadByUser | Avg| 26ms| 26ms | 0s | 0.000
| | P99| 50ms| 50ms | 0s | 0.000
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 340ms| 336ms | -4ms | -1.177
| | P99| 969ms| 956ms | -13ms | -1.341
| upsertDraft | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| viewChannel | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
