### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| TokenStore.Cleanup | avg | 2ms | 9ms | 7ms | 350.39
| CommandWebhookStore.Cleanup | avg | 2ms | 6ms | 4ms | 194.80
| StatusStore.SaveOrUpdate | avg | 4ms | 7ms | 3ms | 79.25
| DraftStore.DeleteDraftsAssociatedWithPost | avg | 10ms | 15ms | 5ms | 50.55
| ChannelBookmarkStore.Save | avg | 8ms | 11ms | 3ms | 36.51
| PostStore.SetPostReminder | avg | 7ms | 9ms | 2ms | 27.61
| ChannelStore.UpdateSidebarCategories | avg | 32ms | 35ms | 3ms | 9.27
| ChannelStore.AutocompleteInTeamForSearch | avg | 263ms | 286ms | 23ms | 8.73
| UserStore.AutocompleteUsersInChannel | avg | 129ms | 132ms | 3ms | 2.32
| PostStore.AnalyticsPostCount | avg | 584ms | 595ms | 11ms | 1.88
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| StatusStore.SaveOrUpdate | p99 | 9ms | 87ms | 78ms | 828.71
| TokenStore.Cleanup | p99 | 5ms | 25ms | 20ms | 403.84
| ChannelBookmarkStore.Save | p99 | 10ms | 25ms | 15ms | 150.75
| PostStore.SetPostReminder | p99 | 10ms | 23ms | 13ms | 130.65
| ChannelStore.GetSidebarCategory | p99 | 10ms | 20ms | 10ms | 101.17
| SessionStore.Remove | p99 | 5ms | 10ms | 5ms | 101.01
| JobStore.GetNewestJobByStatusesAndType | p99 | 5ms | 10ms | 5ms | 101.01
| CommandWebhookStore.Cleanup | p99 | 5ms | 10ms | 5ms | 100.96
| DraftStore.DeleteDraftsAssociatedWithPost | p99 | 25ms | 49ms | 24ms | 97.96
| PostStore.GetPostReminderMetadata | p99 | 5ms | 9ms | 4ms | 80.81
| JobStore.GetCountByStatusAndType | p99 | 5ms | 8ms | 3ms | 60.61
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 5ms | 8ms | 3ms | 60.14
| ChannelStore.GetAllChannelMembersForUser | p99 | 6ms | 9ms | 3ms | 47.62
| ChannelStore.SearchGroupChannels | p99 | 5ms | 7ms | 2ms | 40.27
| ThreadStore.GetThreadForUser | p99 | 6ms | 8ms | 2ms | 30.99
| ChannelStore.AutocompleteInTeamForSearch | p99 | 2.336s | 2.742s | 406ms | 17.38
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 12ms | 14ms | 2ms | 16.56
| FileInfoStore.SetContent | p99 | 20ms | 23ms | 3ms | 15.19
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 17ms | 19ms | 2ms | 11.74
| ChannelStore.GetByName | p99 | 17ms | 19ms | 2ms | 11.55
| ChannelStore.CreateDirectChannel | p99 | 37ms | 39ms | 2ms | 5.41
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 88ms | 91ms | 3ms | 3.40
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelBookmarkStore.Delete | avg | 6ms | 0s | -6ms | -107.14
| PostStore.SearchPostsForUser | avg | 90ms | 64ms | -26ms | -28.85
| StatusStore.UpdateExpiredDNDStatuses | avg | 8ms | 6ms | -2ms | -23.64
| UserStore.Count | avg | 66ms | 51ms | -15ms | -22.62
| UserStore.GetAllProfilesInChannel | avg | 195ms | 192ms | -3ms | -1.54
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelBookmarkStore.Get | p99 | 5ms | 0s | -5ms | -101.01
| ChannelBookmarkStore.Delete | p99 | 10ms | 0s | -10ms | -100.50
| LinkMetadataStore.Save | p99 | 21ms | 5ms | -16ms | -75.29
| JobStore.Get | p99 | 18ms | 5ms | -13ms | -72.42
| TeamStore.GetActiveMemberCount | p99 | 241ms | 100ms | -141ms | -58.51
| StatusStore.UpdateExpiredDNDStatuses | p99 | 22ms | 10ms | -12ms | -53.45
| ChannelStore.GetTeamChannels | p99 | 49ms | 25ms | -24ms | -49.48
| PostStore.SearchPostsForUser | p99 | 2.037s | 1.11s | -927ms | -45.51
| ThreadStore.MarkAllAsReadByChannels | p99 | 9ms | 5ms | -4ms | -44.94
| BotStore.Get | p99 | 9ms | 5ms | -4ms | -43.96
| PreferenceStore.DeleteCategoryAndName | p99 | 9ms | 5ms | -4ms | -42.11
| PostStore.Update | p99 | 40ms | 25ms | -15ms | -37.86
| UserStore.GetAllProfiles | p99 | 8ms | 6ms | -2ms | -23.60
| JobStore.Save | p99 | 10ms | 8ms | -2ms | -20.99
| ChannelStore.GetMember | p99 | 10ms | 8ms | -2ms | -20.24
| UserStore.UpdateUpdateAt | p99 | 15ms | 12ms | -3ms | -19.62
| PreferenceStore.Save | p99 | 34ms | 30ms | -4ms | -11.70
| ThreadStore.MaintainMembership | p99 | 20ms | 18ms | -2ms | -9.83
| UserStore.AutocompleteUsersInChannel | p99 | 357ms | 339ms | -18ms | -5.05
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| setPostReminder | avg | 12ms | 15ms | 3ms | 24.82
| createChannel | avg | 191ms | 211ms | 20ms | 10.47
| updateCategoriesForTeamForUser | avg | 43ms | 47ms | 4ms | 9.27
| autocompleteChannelsForTeamForSearch | avg | 263ms | 286ms | 23ms | 8.73
| autocompleteUsers | avg | 103ms | 108ms | 5ms | 4.85
| uploadFileStream | avg | 366ms | 383ms | 17ms | 4.64
| removeUserCustomStatus | avg | 86ms | 89ms | 3ms | 3.49
| addChannelMember | avg | 138ms | 141ms | 3ms | 2.18
| createDirectChannel | avg | 147ms | 150ms | 3ms | 2.04
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| setPostReminder | p99 | 25ms | 47ms | 22ms | 88.61
| searchGroupChannels | p99 | 5ms | 7ms | 2ms | 40.23
| getPostThread | p99 | 10ms | 12ms | 2ms | 20.00
| autocompleteChannelsForTeamForSearch | p99 | 2.336s | 2.742s | 406ms | 17.38
| getFilePreview | p99 | 94ms | 100ms | 6ms | 6.37
| updateCategoriesForTeamForUser | p99 | 96ms | 99ms | 3ms | 3.12
| getProfileImage | p99 | 287ms | 295ms | 8ms | 2.79
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| searchPostsInTeam | avg | 93ms | 67ms | -26ms | -27.81
| logout | avg | 22ms | 20ms | -2ms | -9.02
| createGroupChannel | avg | 216ms | 205ms | -11ms | -5.10
| getProfileImage | avg | 76ms | 73ms | -3ms | -3.93
| login | avg | 57ms | 55ms | -2ms | -3.53
| addTeamMember | avg | 644ms | 630ms | -14ms | -2.17
| createUser | avg | 108ms | 106ms | -2ms | -1.86
| createPost | avg | 151ms | 149ms | -2ms | -1.32
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getTeamStats | p99 | 245ms | 100ms | -145ms | -59.06
| logout | p99 | 49ms | 25ms | -24ms | -49.36
| searchPostsInTeam | p99 | 2.037s | 1.11s | -927ms | -45.51
| getUsers | p99 | 13ms | 10ms | -3ms | -22.31
| getChannelMember | p99 | 24ms | 21ms | -3ms | -12.76
| addTeamMember | p99 | 2.059s | 1.964s | -95ms | -4.61
| autocompleteUsers | p99 | 311ms | 301ms | -10ms | -3.22
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 19ms| 19ms | 0s | 0.000
| BotStore.Get |  Avg| 2ms| 1ms | -1ms | -62.416
| |  P99| 9ms| 5ms | -4ms | -43.956
| ChannelBookmarkStore.Delete |  Avg| 6ms| 0s | -6ms | -107.136
| |  P99| 10ms| 0s | -10ms | -100.503
| ChannelBookmarkStore.Get |  Avg| 1ms| 0s | -1ms | -131.779
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelBookmarkStore.Save |  Avg| 8ms| 11ms | 3ms | 36.510
| |  P99| 10ms| 25ms | 15ms | 150.754
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 12ms| 14ms | 2ms | 16.560
| ChannelStore.Autocomplete |  Avg| 942ms| 951ms | 9ms | 0.956
| |  P99| 2.459s| 2.459s | 0s | 0.000
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 263ms| 286ms | 23ms | 8.732
| |  P99| 2.336s| 2.742s | 406ms | 17.382
| ChannelStore.CreateDirectChannel |  Avg| 19ms| 18ms | -1ms | -5.351
| |  P99| 37ms| 39ms | 2ms | 5.405
| ChannelStore.CreateInitialSidebarCategories |  Avg| 20ms| 20ms | 0s | 0.000
| |  P99| 48ms| 48ms | 0s | 0.000
| ChannelStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetAllChannelMembersForUser |  Avg| 1ms| 2ms | 1ms | 67.980
| |  P99| 6ms| 9ms | 3ms | 47.616
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 12ms| 13ms | 1ms | 8.433
| |  P99| 88ms| 91ms | 3ms | 3.397
| ChannelStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 17ms| 19ms | 2ms | 11.553
| ChannelStore.GetChannelUnread |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannels |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannelsByUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetFileCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetGuestCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 6ms | 1ms | 20.002
| ChannelStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 8ms | -2ms | -20.240
| ChannelStore.GetMemberCount |  Avg| 61ms| 61ms | 0s | 0.000
| |  P99| 245ms| 245ms | 0s | 0.000
| ChannelStore.GetMemberForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMemberLastViewedAt |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMembersForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetPinnedPostCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetPublicChannelsForTeam |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 17ms| 19ms | 2ms | 11.742
| ChannelStore.GetSidebarCategory |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 10ms| 20ms | 10ms | 101.167
| ChannelStore.GetTeamChannels |  Avg| 22ms| 21ms | -1ms | -4.458
| |  P99| 49ms| 25ms | -24ms | -49.483
| ChannelStore.IncrementMentionCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 7ms | -1ms | -13.002
| ChannelStore.IsReadOnlyChannel |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.Save |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 48ms| 49ms | 1ms | 2.069
| ChannelStore.SaveMember |  Avg| 21ms| 21ms | 0s | 0.000
| |  P99| 50ms| 50ms | 0s | 0.000
| ChannelStore.SearchGroupChannels |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 7ms | 2ms | 40.274
| ChannelStore.UpdateLastViewedAt |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ChannelStore.UpdateSidebarCategories |  Avg| 32ms| 35ms | 3ms | 9.270
| |  P99| 50ms| 50ms | 0s | 0.000
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.422
| CommandWebhookStore.Cleanup |  Avg| 2ms| 6ms | 4ms | 194.805
| |  P99| 5ms| 10ms | 5ms | 100.959
| DraftStore.Delete |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 10ms| 15ms | 5ms | 50.554
| |  P99| 25ms| 49ms | 24ms | 97.959
| DraftStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.GetDraftsForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Upsert |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.299
| EmojiStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| EmojiStore.GetMultipleByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.AttachToPost |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 11ms| 10ms | -1ms | -9.460
| FileInfoStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.GetByIds |  Avg| 2ms| 1ms | -1ms | -66.480
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.Save |  Avg| 5ms| 4ms | -1ms | -21.816
| |  P99| 10ms| 10ms | 0s | 0.000
| FileInfoStore.SetContent |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 20ms| 23ms | 3ms | 15.190
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| GroupStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| GroupStore.GetGroups |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 18ms| 5ms | -13ms | -72.423
| JobStore.GetAllByStatus |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.GetCountByStatusAndType |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 8ms | 3ms | 60.606
| JobStore.GetNewestJobByStatusesAndType |  Avg| 2ms| 1ms | -1ms | -58.090
| |  P99| 5ms| 10ms | 5ms | 101.010
| JobStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 8ms | -2ms | -20.986
| JobStore.UpdateOptimistically |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| JobStore.UpdateStatus |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| JobStore.UpdateStatusOptimistically |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| LinkMetadataStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 21ms| 5ms | -16ms | -75.295
| PluginStore.Delete |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PluginStore.List |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PluginStore.SetWithOptions |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 20ms| 19ms | -1ms | -4.895
| PostAcknowledgementStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostAcknowledgementStore.GetForPosts |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| PostPersistentNotificationStore.DeleteExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.GetSingle |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPriorityStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPriorityStore.GetForPosts |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| PostStore.AnalyticsPostCount |  Avg| 584ms| 595ms | 11ms | 1.884
| |  P99| 995ms| 995ms | 0s | 0.000
| PostStore.Delete |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| PostStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.GetEtag |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.322
| PostStore.GetPostIdBeforeTime |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostReminderMetadata |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.808
| PostStore.GetPostReminders |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| PostStore.GetPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 21ms | 0s | 0.000
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
| |  P99| 47ms| 47ms | 0s | 0.000
| PostStore.SearchPostsForUser |  Avg| 90ms| 64ms | -26ms | -28.850
| |  P99| 2.037s| 1.11s | -927ms | -45.511
| PostStore.SetPostReminder |  Avg| 7ms| 9ms | 2ms | 27.608
| |  P99| 10ms| 23ms | 13ms | 130.653
| PostStore.Update |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 40ms| 25ms | -15ms | -37.855
| PreferenceStore.DeleteCategoryAndName |  Avg| 3ms| 2ms | -1ms | -34.495
| |  P99| 9ms| 5ms | -4ms | -42.106
| PreferenceStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PreferenceStore.GetAll |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.029
| PreferenceStore.Save |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 34ms| 30ms | -4ms | -11.700
| ProductNoticesStore.ClearOldNotices |  Avg| 2ms| 3ms | 1ms | 40.728
| |  P99| 5ms| 5ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 33ms| 32ms | -1ms | -3.034
| |  P99| 89ms| 88ms | -1ms | -1.121
| ReactionStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 7ms | -1ms | -11.774
| RoleStore.ChannelHigherScopedPermissions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| RoleStore.GetByNames |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetPendingScheduledPosts |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.UpdateOldScheduledPosts |  Avg| 3ms| 2ms | -1ms | -39.526
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Get |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 19ms| 19ms | 0s | 0.000
| SessionStore.GetLRUSessions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsExpired |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Remove |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 10ms | 5ms | 101.010
| SessionStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 18ms| 17ms | -1ms | -5.443
| SessionStore.UpdateLastActivityAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| SharedChannelStore.HasChannel |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.GetByIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.SaveOrUpdate |  Avg| 4ms| 7ms | 3ms | 79.254
| |  P99| 9ms| 87ms | 78ms | 828.706
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 8ms| 6ms | -2ms | -23.637
| |  P99| 22ms| 10ms | -12ms | -53.452
| StatusStore.UpdateLastActivityAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 7ms | -1ms | -12.148
| SystemStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| TeamStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetActiveMemberCount |  Avg| 98ms| 97ms | -1ms | -1.018
| |  P99| 241ms| 100ms | -141ms | -58.506
| TeamStore.GetAllPage |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 1ms| 2ms | 1ms | 83.523
| |  P99| 5ms| 8ms | 3ms | 60.142
| TeamStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 7ms | -1ms | -12.679
| TeamStore.GetTeamsByUserId |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -16.064
| TeamStore.GetTeamsForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 6ms | 1ms | 20.062
| TeamStore.GetTotalMemberCount |  Avg| 74ms| 73ms | -1ms | -1.350
| |  P99| 100ms| 100ms | 0s | 0.000
| TeamStore.SaveMember |  Avg| 68ms| 68ms | 0s | 0.000
| |  P99| 100ms| 100ms | 0s | 0.000
| ThreadStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetMembershipForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetTeamsUnreadForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.321
| ThreadStore.GetThreadFollowers |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetThreadForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 8ms | 2ms | 30.994
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
| |  P99| 20ms| 18ms | -2ms | -9.834
| ThreadStore.MarkAllAsReadByChannels |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -44.943
| ThreadStore.MarkAsRead |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.365
| ThreadStore.UpdateMembership |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.298
| TokenStore.Cleanup |  Avg| 2ms| 9ms | 7ms | 350.386
| |  P99| 5ms| 25ms | 20ms | 403.837
| UserAccessTokenStore.GetByToken |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AutocompleteUsersInChannel |  Avg| 129ms| 132ms | 3ms | 2.321
| |  P99| 357ms| 339ms | -18ms | -5.048
| UserStore.Count |  Avg| 66ms| 51ms | -15ms | -22.621
| |  P99| 99ms| 99ms | 0s | 0.000
| UserStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -17.158
| UserStore.GetAllProfiles |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 6ms | -2ms | -23.603
| UserStore.GetAllProfilesInChannel |  Avg| 195ms| 192ms | -3ms | -1.536
| |  P99| 495ms| 496ms | 1ms | 0.202
| UserStore.GetByUsername |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetForLogin |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetMany |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfileByIds |  Avg| 1ms| 2ms | 1ms | 67.696
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfilesByUsernames |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfilesInChannel |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfilesNotInChannel |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetUnreadCount |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 8ms| 7ms | -1ms | -11.991
| UserStore.IsEmpty |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.Save |  Avg| 69ms| 68ms | -1ms | -1.443
| |  P99| 100ms| 100ms | 0s | 0.000
| UserStore.Search |  Avg| 28ms| 28ms | 0s | 0.000
| |  P99| 240ms| 242ms | 2ms | 0.832
| UserStore.Update |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| UserStore.UpdateFailedPasswordAttempts |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 15ms| 16ms | 1ms | 6.539
| UserStore.UpdateLastLogin |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 13ms| 13ms | 0s | 0.000
| UserStore.UpdateUpdateAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 15ms| 12ms | -3ms | -19.615
| UserTermsOfServiceStore.GetByUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| WebhookStore.GetOutgoingByTeam |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 11ms| 10ms | -1ms | -9.024
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 138ms| 141ms | 3ms | 2.176
| | P99| 248ms| 248ms | 0s | 0.000
| addTeamMember | Avg| 644ms| 630ms | -14ms | -2.173
| | P99| 2.059s| 1.964s | -95ms | -4.614
| autocompleteChannelsForTeamForSearch | Avg| 263ms| 286ms | 23ms | 8.730
| | P99| 2.336s| 2.742s | 406ms | 17.382
| autocompleteUsers | Avg| 103ms| 108ms | 5ms | 4.855
| | P99| 311ms| 301ms | -10ms | -3.216
| createChannel | Avg| 191ms| 211ms | 20ms | 10.469
| | P99| 249ms| 249ms | 0s | 0.000
| createChannelBookmark | Avg| 15ms| 15ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| createDirectChannel | Avg| 147ms| 150ms | 3ms | 2.041
| | P99| 248ms| 248ms | 0s | 0.000
| createGroupChannel | Avg| 216ms| 205ms | -11ms | -5.101
| | P99| 491ms| 487ms | -4ms | -0.815
| createPost | Avg| 151ms| 149ms | -2ms | -1.323
| | P99| 807ms| 805ms | -2ms | -0.248
| createUser | Avg| 108ms| 106ms | -2ms | -1.856
| | P99| 248ms| 247ms | -1ms | -0.404
| deleteDraft | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 7ms| 6ms | -1ms | -14.575
| deletePost | Avg| 19ms| 19ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| followThreadByUser | Avg| 9ms| 10ms | 1ms | 10.749
| | P99| 25ms| 25ms | 0s | 0.000
| getAllTeams | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 9ms| 9ms | 0s | 0.000
| getCategoriesForTeamForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 18ms| 19ms | 1ms | 5.672
| getChannel | Avg| 2ms| 3ms | 1ms | 42.133
| | P99| 10ms| 9ms | -1ms | -9.570
| getChannelMember | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 24ms| 21ms | -3ms | -12.757
| getChannelMembersForTeamForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 8ms| 8ms | 0s | 0.000
| getChannelStats | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 203ms| 202ms | -1ms | -0.493
| getChannelUnread | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getChannelsForTeamForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 9ms| 8ms | -1ms | -11.356
| getChannelsForUser | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getClientConfig | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 24ms| 24ms | 0s | 0.000
| getDrafts | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getFilePreview | Avg| 37ms| 38ms | 1ms | 2.690
| | P99| 94ms| 100ms | 6ms | 6.371
| getFileThumbnail | Avg| 31ms| 31ms | 0s | 0.000
| | P99| 87ms| 88ms | 1ms | 1.153
| getPostThread | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 10ms| 12ms | 2ms | 19.999
| getPostsForChannel | Avg| 12ms| 12ms | 0s | 0.000
| | P99| 84ms| 84ms | 0s | 0.000
| getPostsForChannelAroundLastUnread | Avg| 14ms| 14ms | 0s | 0.000
| | P99| 48ms| 47ms | -1ms | -2.087
| getPreferences | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| getProfileImage | Avg| 76ms| 73ms | -3ms | -3.929
| | P99| 287ms| 295ms | 8ms | 2.790
| getPublicChannelsForTeam | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 23ms| 23ms | 0s | 0.000
| getTeamMember | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getTeamMembersForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| getTeamStats | Avg| 98ms| 97ms | -1ms | -1.017
| | P99| 245ms| 100ms | -145ms | -59.063
| getTeamsForUser | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 6ms| 5ms | -1ms | -15.712
| getTeamsUnreadForUser | Avg| 2ms| 3ms | 1ms | 42.785
| | P99| 11ms| 11ms | 0s | 0.000
| getThreadsForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 9ms| 9ms | 0s | 0.000
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 13ms| 10ms | -3ms | -22.307
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsersByNames | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| listChannelBookmarksForChannel | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| login | Avg| 57ms| 55ms | -2ms | -3.526
| | P99| 244ms| 243ms | -1ms | -0.410
| logout | Avg| 22ms| 20ms | -2ms | -9.025
| | P99| 49ms| 25ms | -24ms | -49.356
| patchPost | Avg| 22ms| 22ms | 0s | 0.000
| | P99| 48ms| 48ms | 0s | 0.000
| removeUserCustomStatus | Avg| 86ms| 89ms | 3ms | 3.487
| | P99| 246ms| 245ms | -1ms | -0.406
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| searchAllChannels | Avg| 942ms| 951ms | 9ms | 0.955
| | P99| 2.459s| 2.459s | 0s | 0.000
| searchGroupChannels | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 7ms | 2ms | 40.231
| searchPostsInTeam | Avg| 93ms| 67ms | -26ms | -27.812
| | P99| 2.037s| 1.11s | -927ms | -45.511
| searchUsers | Avg| 29ms| 29ms | 0s | 0.000
| | P99| 241ms| 243ms | 2ms | 0.830
| setPostReminder | Avg| 12ms| 15ms | 3ms | 24.821
| | P99| 25ms| 47ms | 22ms | 88.608
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| updateCategoriesForTeamForUser | Avg| 43ms| 47ms | 4ms | 9.267
| | P99| 96ms| 99ms | 3ms | 3.117
| updatePreferences | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| updateReadStateThreadByUser | Avg| 16ms| 16ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 366ms| 383ms | 17ms | 4.644
| | P99| 977ms| 982ms | 5ms | 0.512
| upsertDraft | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| viewChannel | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
