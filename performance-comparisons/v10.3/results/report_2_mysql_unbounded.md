### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.AutocompleteInTeamForSearch | avg | 77ms | 159ms | 82ms | 105.87
| StatusStore.SaveOrUpdate | avg | 5ms | 8ms | 3ms | 61.56
| PostStore.SearchPostsForUser | avg | 36ms | 55ms | 19ms | 52.98
| ChannelStore.GetTeamChannels | avg | 25ms | 27ms | 2ms | 8.12
| UserStore.Count | avg | 71ms | 74ms | 3ms | 4.21
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.AutocompleteInTeamForSearch | p99 | 263ms | 1.991s | 1.728s | 656.02
| PostStore.SearchPostsForUser | p99 | 243ms | 1.282s | 1.039s | 427.15
| StatusStore.SaveOrUpdate | p99 | 22ms | 85ms | 63ms | 283.65
| JobStore.GetCountByStatusAndType | p99 | 5ms | 15ms | 10ms | 202.02
| JobStore.GetAllByStatus | p99 | 8ms | 20ms | 12ms | 155.84
| UserStore.Count | p99 | 99ms | 240ms | 141ms | 141.84
| PostStore.SetPostReminder | p99 | 10ms | 24ms | 14ms | 140.70
| UserStore.GetProfilesInChannel | p99 | 9ms | 22ms | 13ms | 139.79
| ClusterDiscoveryStore.SetLastPingAt | p99 | 10ms | 23ms | 13ms | 135.18
| JobStore.UpdateStatusOptimistically | p99 | 10ms | 20ms | 10ms | 101.57
| StatusStore.UpdateExpiredDNDStatuses | p99 | 24ms | 44ms | 20ms | 84.21
| UserStore.GetMany | p99 | 5ms | 8ms | 3ms | 60.61
| ChannelStore.UpdateSidebarChannelsByPreferences | p99 | 5ms | 8ms | 3ms | 60.04
| ChannelStore.GetGuestCount | p99 | 9ms | 13ms | 4ms | 44.39
| ChannelStore.GetMember | p99 | 10ms | 14ms | 4ms | 41.51
| ChannelStore.GetByName | p99 | 22ms | 31ms | 9ms | 40.68
| JobStore.Get | p99 | 5ms | 7ms | 2ms | 40.40
| EmojiStore.GetByName | p99 | 5ms | 7ms | 2ms | 40.05
| DraftStore.Upsert | p99 | 10ms | 14ms | 4ms | 39.23
| WebhookStore.GetOutgoingByTeam | p99 | 24ms | 33ms | 9ms | 37.89
| UserStore.UpdateFailedPasswordAttempts | p99 | 13ms | 18ms | 5ms | 37.32
| ChannelBookmarkStore.GetBookmarksForChannelSince | p99 | 5ms | 7ms | 2ms | 36.98
| StatusStore.GetByIds | p99 | 6ms | 8ms | 2ms | 35.81
| ThreadStore.GetTotalUnreadMentions | p99 | 9ms | 12ms | 3ms | 33.23
| ThreadStore.GetMembershipForUser | p99 | 6ms | 8ms | 2ms | 31.66
| TeamStore.GetMember | p99 | 7ms | 9ms | 2ms | 30.07
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 7ms | 9ms | 2ms | 29.24
| PreferenceStore.Save | p99 | 31ms | 40ms | 9ms | 28.93
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 7ms | 9ms | 2ms | 28.83
| PostStore.GetPostIdAfterTime | p99 | 7ms | 9ms | 2ms | 26.76
| PostStore.GetPostsAfter | p99 | 8ms | 10ms | 2ms | 25.71
| UserStore.GetUnreadCount | p99 | 20ms | 25ms | 5ms | 25.33
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 8ms | 10ms | 2ms | 24.54
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 13ms | 16ms | 3ms | 23.38
| UserStore.UpdateUpdateAt | p99 | 13ms | 16ms | 3ms | 23.32
| UserStore.Save | p99 | 100ms | 123ms | 23ms | 23.04
| ThreadStore.GetThreadFollowers | p99 | 9ms | 11ms | 2ms | 22.18
| UserStore.UpdateLastLogin | p99 | 10ms | 12ms | 2ms | 20.10
| PostStore.GetEtag | p99 | 10ms | 12ms | 2ms | 20.01
| ChannelStore.GetSidebarCategory | p99 | 16ms | 19ms | 3ms | 19.11
| PreferenceStore.GetAll | p99 | 11ms | 13ms | 2ms | 17.85
| FileInfoStore.Save | p99 | 17ms | 20ms | 3ms | 17.33
| TeamStore.SaveMember | p99 | 100ms | 113ms | 13ms | 13.02
| ChannelStore.SaveMember | p99 | 66ms | 71ms | 5ms | 7.62
| ChannelStore.UpdateSidebarCategories | p99 | 92ms | 97ms | 5ms | 5.42
| ChannelStore.CreateInitialSidebarCategories | p99 | 48ms | 50ms | 2ms | 4.13
| ProductNoticesStore.View | p99 | 96ms | 98ms | 2ms | 2.08
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| BotStore.Save | avg | 6ms | 0s | -6ms | -106.10
| ChannelStore.GetAllChannelMemberIdsByChannelId | avg | 9ms | 0s | -9ms | -104.88
| ThreadStore.MarkAllAsReadByTeam | avg | 4ms | 0s | -4ms | -101.96
| ChannelStore.CreateSidebarCategory | avg | 25ms | 0s | -25ms | -98.52
| ChannelStore.GetMembers | avg | 2ms | 0s | -2ms | -80.78
| ChannelStore.GetAllChannelMembersForUser | avg | 6ms | 2ms | -4ms | -66.62
| ChannelStore.GetMemberCount | avg | 103ms | 75ms | -28ms | -27.15
| ChannelBookmarkStore.Delete | avg | 9ms | 7ms | -2ms | -23.33
| ChannelStore.GetPublicChannelsForTeam | avg | 10ms | 8ms | -2ms | -19.96
| TeamStore.GetTotalMemberCount | avg | 101ms | 82ms | -19ms | -18.86
| PostStore.AnalyticsPostCount | avg | 926ms | 780ms | -146ms | -15.77
| TeamStore.GetActiveMemberCount | avg | 135ms | 114ms | -21ms | -15.50
| UserStore.GetAllProfilesInChannel | avg | 298ms | 266ms | -32ms | -10.75
| ChannelStore.Autocomplete | avg | 968ms | 952ms | -16ms | -1.65
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.GetAllChannelMemberIdsByChannelId | p99 | 25ms | 0s | -25ms | -101.32
| ThreadStore.MarkAllAsReadByTeam | p99 | 10ms | 0s | -10ms | -101.01
| ChannelStore.GetMembers | p99 | 5ms | 0s | -5ms | -101.01
| RetentionPolicyStore.GetAll | p99 | 5ms | 0s | -5ms | -101.01
| RetentionPolicyStore.GetCount | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.CreateSidebarCategory | p99 | 50ms | 0s | -50ms | -100.50
| BotStore.Save | p99 | 10ms | 0s | -10ms | -100.50
| UserStore.Update | p99 | 53ms | 12ms | -41ms | -77.36
| PostStore.AnalyticsPostCount | p99 | 2.47s | 995ms | -1.475s | -59.72
| SessionStore.Remove | p99 | 24ms | 10ms | -14ms | -59.38
| TeamStore.GetTotalMemberCount | p99 | 245ms | 100ms | -145ms | -59.30
| ChannelStore.GetAllChannelMembersForUser | p99 | 25ms | 11ms | -14ms | -56.24
| PreferenceStore.DeleteCategoryAndName | p99 | 22ms | 10ms | -12ms | -53.81
| LinkMetadataStore.Save | p99 | 18ms | 9ms | -9ms | -49.72
| PostStore.Delete | p99 | 45ms | 25ms | -20ms | -43.96
| BotStore.Get | p99 | 9ms | 5ms | -4ms | -42.67
| PluginStore.List | p99 | 8ms | 5ms | -3ms | -40.00
| JobStore.Save | p99 | 33ms | 20ms | -13ms | -39.10
| PostPersistentNotificationStore.DeleteExpired | p99 | 8ms | 5ms | -3ms | -37.74
| PostPersistentNotificationStore.Get | p99 | 8ms | 5ms | -3ms | -37.74
| JobStore.GetNewestJobByStatusesAndType | p99 | 10ms | 7ms | -3ms | -31.50
| PostAcknowledgementStore.GetForPost | p99 | 9ms | 7ms | -2ms | -21.98
| ReactionStore.GetForPost | p99 | 10ms | 8ms | -2ms | -20.73
| UserStore.GetAllProfilesInChannel | p99 | 796ms | 654ms | -142ms | -17.84
| ChannelStore.GetPublicChannelsForTeam | p99 | 25ms | 22ms | -3ms | -12.10
| PostStore.GetPostReminders | p99 | 23ms | 21ms | -2ms | -8.65
| UserStore.AutocompleteUsersInChannel | p99 | 426ms | 403ms | -23ms | -5.40
| ChannelStore.Save | p99 | 48ms | 46ms | -2ms | -4.18
| ChannelStore.GetMemberCount | p99 | 250ms | 247ms | -3ms | -1.20
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| autocompleteChannelsForTeamForSearch | avg | 78ms | 159ms | 81ms | 104.51
| searchPostsInTeam | avg | 41ms | 60ms | 19ms | 46.88
| createChannel | avg | 173ms | 217ms | 44ms | 25.46
| viewChannel | avg | 11ms | 13ms | 2ms | 17.40
| followThreadByUser | avg | 12ms | 14ms | 2ms | 16.90
| setPostReminder | avg | 16ms | 18ms | 2ms | 12.23
| createGroupChannel | avg | 216ms | 236ms | 20ms | 9.27
| addChannelMember | avg | 145ms | 155ms | 10ms | 6.87
| createDirectChannel | avg | 138ms | 145ms | 7ms | 5.09
| createUser | avg | 121ms | 127ms | 6ms | 4.94
| removeUserCustomStatus | avg | 97ms | 99ms | 2ms | 2.06
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| autocompleteChannelsForTeamForSearch | p99 | 263ms | 1.991s | 1.728s | 656.02
| searchPostsInTeam | p99 | 249ms | 1.282s | 1.033s | 415.67
| unfollowThreadByUser | p99 | 25ms | 61ms | 36ms | 144.88
| createChannel | p99 | 248ms | 493ms | 245ms | 98.59
| followThreadByUser | p99 | 25ms | 48ms | 23ms | 92.56
| getTeamMember | p99 | 5ms | 9ms | 4ms | 74.33
| viewChannel | p99 | 25ms | 39ms | 14ms | 56.02
| createDirectChannel | p99 | 311ms | 453ms | 142ms | 45.62
| addChannelMember | p99 | 249ms | 358ms | 109ms | 43.72
| getUser | p99 | 10ms | 14ms | 4ms | 40.79
| createUser | p99 | 306ms | 375ms | 69ms | 22.57
| getTeamMembersForUser | p99 | 10ms | 12ms | 2ms | 20.18
| upsertDraft | p99 | 15ms | 18ms | 3ms | 20.07
| getPreferences | p99 | 12ms | 14ms | 2ms | 16.90
| getChannelMember | p99 | 20ms | 23ms | 3ms | 14.81
| getUsers | p99 | 14ms | 16ms | 2ms | 14.17
| getPostsForChannelAroundLastUnread | p99 | 50ms | 55ms | 5ms | 10.01
| saveReaction | p99 | 22ms | 24ms | 2ms | 9.27
| getPostsForChannel | p99 | 178ms | 180ms | 2ms | 1.12
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getChannelMembers | avg | 3ms | 0s | -3ms | -101.45
| updateReadStateAllThreadsByUser | avg | 4ms | 0s | -4ms | -100.35
| createCategoryForTeamForUser | avg | 27ms | 0s | -27ms | -98.88
| createPost | avg | 339ms | 244ms | -95ms | -28.02
| createChannelBookmark | avg | 18ms | 13ms | -5ms | -27.28
| getFilePreview | avg | 50ms | 37ms | -13ms | -26.07
| getProfileImage | avg | 96ms | 72ms | -24ms | -25.08
| getChannelStats | avg | 12ms | 9ms | -3ms | -24.43
| getPublicChannelsForTeam | avg | 11ms | 9ms | -2ms | -18.28
| getTeamStats | avg | 138ms | 114ms | -24ms | -17.39
| patchPost | avg | 36ms | 30ms | -6ms | -16.50
| logout | avg | 35ms | 32ms | -3ms | -8.67
| addTeamMember | avg | 789ms | 732ms | -57ms | -7.22
| uploadFileStream | avg | 389ms | 382ms | -7ms | -1.80
| searchAllChannels | avg | 969ms | 952ms | -17ms | -1.76
| autocompleteUsers | avg | 129ms | 127ms | -2ms | -1.55
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| updateReadStateAllThreadsByUser | p99 | 10ms | 0s | -10ms | -101.01
| getChannelMembers | p99 | 5ms | 0s | -5ms | -101.01
| createCategoryForTeamForUser | p99 | 50ms | 0s | -50ms | -100.50
| patchPost | p99 | 400ms | 86ms | -314ms | -78.50
| logout | p99 | 222ms | 50ms | -172ms | -77.65
| getChannel | p99 | 23ms | 11ms | -12ms | -51.13
| updateCategoriesForTeamForUser | p99 | 203ms | 99ms | -104ms | -51.11
| getProfileImage | p99 | 352ms | 277ms | -75ms | -21.33
| autocompleteUsers | p99 | 405ms | 371ms | -34ms | -8.40
| getPublicChannelsForTeam | p99 | 25ms | 23ms | -2ms | -8.02
| removeUserCustomStatus | p99 | 267ms | 247ms | -20ms | -7.48
| getChannelStats | p99 | 233ms | 222ms | -11ms | -4.71
| createPost | p99 | 985ms | 966ms | -19ms | -1.93
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 18ms| 18ms | 0s | 0.000
| BotStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -42.667
| BotStore.Save |  Avg| 6ms| 0s | -6ms | -106.096
| |  P99| 10ms| 0s | -10ms | -100.503
| ChannelBookmarkStore.Delete |  Avg| 9ms| 7ms | -2ms | -23.331
| |  P99| 10ms| 10ms | 0s | 0.000
| ChannelBookmarkStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 7ms | 2ms | 36.979
| ChannelBookmarkStore.Save |  Avg| 11ms| 10ms | -1ms | -8.784
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 13ms| 16ms | 3ms | 23.381
| ChannelStore.Autocomplete |  Avg| 968ms| 952ms | -16ms | -1.652
| |  P99| 2.458s| 2.458s | 0s | 0.000
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 77ms| 159ms | 82ms | 105.874
| |  P99| 263ms| 1.991s | 1.728s | 656.024
| ChannelStore.CreateDirectChannel |  Avg| 22ms| 23ms | 1ms | 4.473
| |  P99| 48ms| 49ms | 1ms | 2.101
| ChannelStore.CreateInitialSidebarCategories |  Avg| 22ms| 22ms | 0s | 0.000
| |  P99| 48ms| 50ms | 2ms | 4.128
| ChannelStore.CreateSidebarCategory |  Avg| 25ms| 0s | -25ms | -98.517
| |  P99| 50ms| 0s | -50ms | -100.503
| ChannelStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 11.834
| ChannelStore.GetAllChannelMemberIdsByChannelId |  Avg| 9ms| 0s | -9ms | -104.880
| |  P99| 25ms| 0s | -25ms | -101.317
| ChannelStore.GetAllChannelMembersForUser |  Avg| 6ms| 2ms | -4ms | -66.621
| |  P99| 25ms| 11ms | -14ms | -56.238
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 12ms| 13ms | 1ms | 8.607
| |  P99| 81ms| 82ms | 1ms | 1.240
| ChannelStore.GetByName |  Avg| 3ms| 4ms | 1ms | 28.687
| |  P99| 22ms| 31ms | 9ms | 40.678
| ChannelStore.GetChannelUnread |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 6ms | 0s | 0.000
| ChannelStore.GetChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ChannelStore.GetChannelsByUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 6ms | -1ms | -14.536
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 7ms | 1ms | 16.889
| ChannelStore.GetFileCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.455
| ChannelStore.GetGuestCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 13ms | 4ms | 44.387
| ChannelStore.GetMember |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 14ms | 4ms | 41.505
| ChannelStore.GetMemberCount |  Avg| 103ms| 75ms | -28ms | -27.150
| |  P99| 250ms| 247ms | -3ms | -1.201
| ChannelStore.GetMemberForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 13.894
| ChannelStore.GetMemberLastViewedAt |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 7ms | 1ms | 17.691
| ChannelStore.GetMembers |  Avg| 2ms| 0s | -2ms | -80.777
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelStore.GetMembersForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ChannelStore.GetPinnedPostCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -17.185
| ChannelStore.GetPublicChannelsForTeam |  Avg| 10ms| 8ms | -2ms | -19.964
| |  P99| 25ms| 22ms | -3ms | -12.100
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| ChannelStore.GetSidebarCategory |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 16ms| 19ms | 3ms | 19.108
| ChannelStore.GetTeamChannels |  Avg| 25ms| 27ms | 2ms | 8.115
| |  P99| 49ms| 49ms | 0s | 0.000
| ChannelStore.IncrementMentionCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 11.117
| ChannelStore.Save |  Avg| 14ms| 13ms | -1ms | -7.192
| |  P99| 48ms| 46ms | -2ms | -4.177
| ChannelStore.SaveMember |  Avg| 26ms| 26ms | 0s | 0.000
| |  P99| 66ms| 71ms | 5ms | 7.620
| ChannelStore.SearchGroupChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 11.966
| ChannelStore.UpdateLastViewedAt |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 20ms| 21ms | 1ms | 4.970
| ChannelStore.UpdateSidebarCategories |  Avg| 40ms| 39ms | -1ms | -2.507
| |  P99| 92ms| 97ms | 5ms | 5.420
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 8ms | 3ms | 60.035
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 4ms| 5ms | 1ms | 23.779
| |  P99| 10ms| 23ms | 13ms | 135.185
| CommandWebhookStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DesktopTokensStore.DeleteOlderThan |  Avg| 3ms| 2ms | -1ms | -37.024
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Delete |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 15ms| 14ms | -1ms | -6.791
| |  P99| 25ms| 25ms | 0s | 0.000
| DraftStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 14.592
| DraftStore.GetDraftsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 11.379
| DraftStore.Upsert |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 14ms | 4ms | 39.234
| EmojiStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 7ms | 2ms | 40.051
| EmojiStore.GetMultipleByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.AttachToPost |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 21ms| 22ms | 1ms | 4.775
| FileInfoStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 7ms | 1ms | 17.089
| FileInfoStore.GetByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| FileInfoStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| FileInfoStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 17ms| 20ms | 3ms | 17.334
| FileInfoStore.SetContent |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 9ms | 2ms | 29.242
| GroupStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| GroupStore.GetGroups |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| JobStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 7ms | 2ms | 40.404
| JobStore.GetAllByStatus |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 20ms | 12ms | 155.844
| JobStore.GetCountByStatusAndType |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 15ms | 10ms | 202.020
| JobStore.GetNewestJobByStatusesAndType |  Avg| 3ms| 2ms | -1ms | -39.449
| |  P99| 10ms| 7ms | -3ms | -31.496
| JobStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 33ms| 20ms | -13ms | -39.098
| JobStore.UpdateOptimistically |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.392
| JobStore.UpdateStatus |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| JobStore.UpdateStatusOptimistically |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 10ms| 20ms | 10ms | 101.568
| LinkMetadataStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 7ms | 1ms | 16.290
| LinkMetadataStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 18ms| 9ms | -9ms | -49.724
| PluginStore.Delete |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 10.749
| PluginStore.List |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 5ms | -3ms | -40.000
| PluginStore.SetWithOptions |  Avg| 6ms| 7ms | 1ms | 15.429
| |  P99| 20ms| 21ms | 1ms | 4.898
| PostAcknowledgementStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 7ms | -2ms | -21.978
| PostAcknowledgementStore.GetForPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 19ms| 20ms | 1ms | 5.180
| PostPersistentNotificationStore.DeleteExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 5ms | -3ms | -37.736
| PostPersistentNotificationStore.Get |  Avg| 3ms| 2ms | -1ms | -39.843
| |  P99| 8ms| 5ms | -3ms | -37.736
| PostPersistentNotificationStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 6ms | 1ms | 19.944
| PostPriorityStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostPriorityStore.GetForPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 19ms| 20ms | 1ms | 5.145
| PostStore.AnalyticsPostCount |  Avg| 926ms| 780ms | -146ms | -15.775
| |  P99| 2.47s| 995ms | -1.475s | -59.717
| PostStore.Delete |  Avg| 16ms| 17ms | 1ms | 6.389
| |  P99| 45ms| 25ms | -20ms | -43.957
| PostStore.Get |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 15ms| 16ms | 1ms | 6.501
| PostStore.GetEtag |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 12ms | 2ms | 20.010
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 7ms| 9ms | 2ms | 26.757
| PostStore.GetPostIdBeforeTime |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| PostStore.GetPostReminderMetadata |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostReminders |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 23ms| 21ms | -2ms | -8.649
| PostStore.GetPosts |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 21ms| 20ms | -1ms | -4.868
| PostStore.GetPostsAfter |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 10ms | 2ms | 25.710
| PostStore.GetPostsBefore |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 10.844
| PostStore.GetPostsByThread |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 6ms | 0s | 0.000
| PostStore.GetPostsSince |  Avg| 8ms| 9ms | 1ms | 11.927
| |  P99| 47ms| 48ms | 1ms | 2.123
| PostStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 6ms | 0s | 0.000
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 14ms| 15ms | 1ms | 6.935
| |  P99| 48ms| 49ms | 1ms | 2.078
| PostStore.SearchPostsForUser |  Avg| 36ms| 55ms | 19ms | 52.985
| |  P99| 243ms| 1.282s | 1.039s | 427.153
| PostStore.SetPostReminder |  Avg| 8ms| 9ms | 1ms | 12.509
| |  P99| 10ms| 24ms | 14ms | 140.704
| PostStore.Update |  Avg| 17ms| 17ms | 0s | 0.000
| |  P99| 40ms| 41ms | 1ms | 2.505
| PreferenceStore.DeleteCategoryAndName |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 22ms| 10ms | -12ms | -53.813
| PreferenceStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 10.714
| PreferenceStore.GetAll |  Avg| 2ms| 3ms | 1ms | 40.951
| |  P99| 11ms| 13ms | 2ms | 17.852
| PreferenceStore.Save |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 31ms| 40ms | 9ms | 28.929
| ProductNoticesStore.ClearOldNotices |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 37ms| 38ms | 1ms | 2.701
| |  P99| 96ms| 98ms | 2ms | 2.082
| ReactionStore.GetForPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 8ms | -2ms | -20.729
| RetentionPolicyStore.GetAll |  Avg| 1ms| 0s | -1ms | -84.881
| |  P99| 5ms| 0s | -5ms | -101.010
| RetentionPolicyStore.GetCount |  Avg| 1ms| 0s | -1ms | -118.347
| |  P99| 5ms| 0s | -5ms | -101.010
| RoleStore.ChannelHigherScopedPermissions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| RoleStore.GetByNames |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Get |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 21ms| 22ms | 1ms | 4.797
| SessionStore.GetLRUSessions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| SessionStore.GetSessionsExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 10ms | 2ms | 24.540
| SessionStore.Remove |  Avg| 6ms| 5ms | -1ms | -17.126
| |  P99| 24ms| 10ms | -14ms | -59.385
| SessionStore.Save |  Avg| 6ms| 7ms | 1ms | 15.512
| |  P99| 21ms| 21ms | 0s | 0.000
| SessionStore.UpdateLastActivityAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| StatusStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.955
| StatusStore.GetByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 8ms | 2ms | 35.814
| StatusStore.SaveOrUpdate |  Avg| 5ms| 8ms | 3ms | 61.559
| |  P99| 22ms| 85ms | 63ms | 283.653
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 9ms| 10ms | 1ms | 11.745
| |  P99| 24ms| 44ms | 20ms | 84.211
| StatusStore.UpdateLastActivityAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| SystemStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| TeamStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 6ms | 1ms | 20.004
| TeamStore.GetActiveMemberCount |  Avg| 135ms| 114ms | -21ms | -15.499
| |  P99| 249ms| 249ms | 0s | 0.000
| TeamStore.GetAllPage |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| TeamStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 9ms | 2ms | 30.074
| TeamStore.GetTeamsByUserId |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| TeamStore.GetTeamsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 13.840
| TeamStore.GetTotalMemberCount |  Avg| 101ms| 82ms | -19ms | -18.861
| |  P99| 245ms| 100ms | -145ms | -59.305
| TeamStore.SaveMember |  Avg| 72ms| 73ms | 1ms | 1.380
| |  P99| 100ms| 113ms | 13ms | 13.021
| ThreadStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetMembershipForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 8ms | 2ms | 31.659
| ThreadStore.GetTeamsUnreadForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.358
| ThreadStore.GetThreadFollowers |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 11ms | 2ms | 22.178
| ThreadStore.GetThreadForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 12ms| 11ms | -1ms | -8.636
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 6ms | 0s | 0.000
| ThreadStore.GetThreadsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.004
| ThreadStore.GetTotalThreads |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 15.095
| ThreadStore.GetTotalUnreadMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 12ms | 3ms | 33.231
| ThreadStore.GetTotalUnreadThreads |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 14.767
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 9ms | 2ms | 28.827
| ThreadStore.MaintainMembership |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 23ms| 24ms | 1ms | 4.323
| ThreadStore.MarkAllAsReadByChannels |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ThreadStore.MarkAllAsReadByTeam |  Avg| 4ms| 0s | -4ms | -101.964
| |  P99| 10ms| 0s | -10ms | -101.010
| ThreadStore.MarkAsRead |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ThreadStore.UpdateMembership |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| TokenStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AutocompleteUsersInChannel |  Avg| 149ms| 148ms | -1ms | -0.670
| |  P99| 426ms| 403ms | -23ms | -5.399
| UserStore.Count |  Avg| 71ms| 74ms | 3ms | 4.209
| |  P99| 99ms| 240ms | 141ms | 141.838
| UserStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 15.217
| UserStore.GetAllProfiles |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| UserStore.GetAllProfilesInChannel |  Avg| 298ms| 266ms | -32ms | -10.754
| |  P99| 796ms| 654ms | -142ms | -17.837
| UserStore.GetByUsername |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 7ms | 1ms | 16.878
| UserStore.GetForLogin |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| UserStore.GetMany |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 8ms | 3ms | 60.606
| UserStore.GetProfileByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.102
| UserStore.GetProfilesByUsernames |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 13.970
| UserStore.GetProfilesInChannel |  Avg| 2ms| 3ms | 1ms | 45.809
| |  P99| 9ms| 22ms | 13ms | 139.786
| UserStore.GetProfilesNotInChannel |  Avg| 6ms| 7ms | 1ms | 17.707
| |  P99| 23ms| 24ms | 1ms | 4.283
| UserStore.GetUnreadCount |  Avg| 3ms| 4ms | 1ms | 36.359
| |  P99| 20ms| 25ms | 5ms | 25.330
| UserStore.IsEmpty |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.Save |  Avg| 66ms| 67ms | 1ms | 1.507
| |  P99| 100ms| 123ms | 23ms | 23.041
| UserStore.Search |  Avg| 66ms| 66ms | 0s | 0.000
| |  P99| 244ms| 244ms | 0s | 0.000
| UserStore.Update |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 53ms| 12ms | -41ms | -77.361
| UserStore.UpdateFailedPasswordAttempts |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 13ms| 18ms | 5ms | 37.323
| UserStore.UpdateLastLogin |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 12ms | 2ms | 20.102
| UserStore.UpdateUpdateAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 13ms| 16ms | 3ms | 23.325
| UserTermsOfServiceStore.GetByUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 13.785
| WebhookStore.GetOutgoingByTeam |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 24ms| 33ms | 9ms | 37.895
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 145ms| 155ms | 10ms | 6.874
| | P99| 249ms| 358ms | 109ms | 43.723
| addTeamMember | Avg| 789ms| 732ms | -57ms | -7.220
| | P99| 2.423s| 2.411s | -12ms | -0.495
| autocompleteChannelsForTeamForSearch | Avg| 78ms| 159ms | 81ms | 104.509
| | P99| 263ms| 1.991s | 1.728s | 656.024
| autocompleteUsers | Avg| 129ms| 127ms | -2ms | -1.554
| | P99| 405ms| 371ms | -34ms | -8.396
| createCategoryForTeamForUser | Avg| 27ms| 0s | -27ms | -98.877
| | P99| 50ms| 0s | -50ms | -100.503
| createChannel | Avg| 173ms| 217ms | 44ms | 25.464
| | P99| 248ms| 493ms | 245ms | 98.592
| createChannelBookmark | Avg| 18ms| 13ms | -5ms | -27.281
| | P99| 25ms| 25ms | 0s | 0.000
| createDirectChannel | Avg| 138ms| 145ms | 7ms | 5.085
| | P99| 311ms| 453ms | 142ms | 45.622
| createGroupChannel | Avg| 216ms| 236ms | 20ms | 9.268
| | P99| 493ms| 495ms | 2ms | 0.406
| createPost | Avg| 339ms| 244ms | -95ms | -28.018
| | P99| 985ms| 966ms | -19ms | -1.929
| createUser | Avg| 121ms| 127ms | 6ms | 4.942
| | P99| 306ms| 375ms | 69ms | 22.566
| deleteDraft | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| deletePost | Avg| 23ms| 24ms | 1ms | 4.379
| | P99| 48ms| 49ms | 1ms | 2.094
| followThreadByUser | Avg| 12ms| 14ms | 2ms | 16.904
| | P99| 25ms| 48ms | 23ms | 92.555
| getAllTeams | Avg| 2ms| 3ms | 1ms | 40.163
| | P99| 10ms| 10ms | 0s | 0.000
| getCategoriesForTeamForUser | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 23ms| 23ms | 0s | 0.000
| getChannel | Avg| 5ms| 4ms | -1ms | -22.009
| | P99| 23ms| 11ms | -12ms | -51.129
| getChannelMember | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 20ms| 23ms | 3ms | 14.815
| getChannelMembers | Avg| 3ms| 0s | -3ms | -101.447
| | P99| 5ms| 0s | -5ms | -101.010
| getChannelMembersForTeamForUser | Avg| 2ms| 3ms | 1ms | 40.432
| | P99| 10ms| 10ms | 0s | 0.000
| getChannelStats | Avg| 12ms| 9ms | -3ms | -24.434
| | P99| 233ms| 222ms | -11ms | -4.713
| getChannelUnread | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 6ms| 6ms | 0s | 0.000
| getChannelsForTeamForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| getChannelsForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 7ms| 6ms | -1ms | -14.410
| getClientConfig | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 24ms| 25ms | 1ms | 4.083
| getDrafts | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 9ms| 10ms | 1ms | 11.021
| getFilePreview | Avg| 50ms| 37ms | -13ms | -26.068
| | P99| 94ms| 93ms | -1ms | -1.065
| getFileThumbnail | Avg| 30ms| 31ms | 1ms | 3.279
| | P99| 83ms| 84ms | 1ms | 1.207
| getPostThread | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| getPostsForChannel | Avg| 21ms| 21ms | 0s | 0.000
| | P99| 178ms| 180ms | 2ms | 1.122
| getPostsForChannelAroundLastUnread | Avg| 19ms| 20ms | 1ms | 5.155
| | P99| 50ms| 55ms | 5ms | 10.009
| getPreferences | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 12ms| 14ms | 2ms | 16.901
| getProfileImage | Avg| 96ms| 72ms | -24ms | -25.078
| | P99| 352ms| 277ms | -75ms | -21.327
| getPublicChannelsForTeam | Avg| 11ms| 9ms | -2ms | -18.284
| | P99| 25ms| 23ms | -2ms | -8.022
| getTeamMember | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 5ms| 9ms | 4ms | 74.332
| getTeamMembersForUser | Avg| 2ms| 3ms | 1ms | 40.767
| | P99| 10ms| 12ms | 2ms | 20.179
| getTeamStats | Avg| 138ms| 114ms | -24ms | -17.390
| | P99| 249ms| 249ms | 0s | 0.000
| getTeamsForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 8ms| 8ms | 0s | 0.000
| getTeamsUnreadForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 17ms| 17ms | 0s | 0.000
| getThreadsForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 9ms| 9ms | 0s | 0.000
| getUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 10ms| 14ms | 4ms | 40.794
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 14ms| 16ms | 2ms | 14.167
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsersByNames | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 7ms| 8ms | 1ms | 13.363
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| listChannelBookmarksForChannel | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 7ms| 8ms | 1ms | 14.493
| login | Avg| 71ms| 72ms | 1ms | 1.412
| | P99| 244ms| 244ms | 0s | 0.000
| logout | Avg| 35ms| 32ms | -3ms | -8.669
| | P99| 222ms| 50ms | -172ms | -77.652
| patchPost | Avg| 36ms| 30ms | -6ms | -16.501
| | P99| 400ms| 86ms | -314ms | -78.500
| removeUserCustomStatus | Avg| 97ms| 99ms | 2ms | 2.061
| | P99| 267ms| 247ms | -20ms | -7.477
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 6ms| 7ms | 1ms | 15.672
| | P99| 22ms| 24ms | 2ms | 9.268
| searchAllChannels | Avg| 969ms| 952ms | -17ms | -1.755
| | P99| 2.458s| 2.458s | 0s | 0.000
| searchGroupChannels | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 8ms| 9ms | 1ms | 11.966
| searchPostsInTeam | Avg| 41ms| 60ms | 19ms | 46.881
| | P99| 249ms| 1.282s | 1.033s | 415.667
| searchUsers | Avg| 67ms| 67ms | 0s | 0.000
| | P99| 244ms| 244ms | 0s | 0.000
| setPostReminder | Avg| 16ms| 18ms | 2ms | 12.233
| | P99| 25ms| 25ms | 0s | 0.000
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 12ms| 13ms | 1ms | 8.099
| | P99| 25ms| 61ms | 36ms | 144.882
| updateCategoriesForTeamForUser | Avg| 54ms| 53ms | -1ms | -1.850
| | P99| 203ms| 99ms | -104ms | -51.106
| updatePreferences | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| updateReadStateAllThreadsByUser | Avg| 4ms| 0s | -4ms | -100.346
| | P99| 10ms| 0s | -10ms | -101.010
| updateReadStateThreadByUser | Avg| 24ms| 24ms | 0s | 0.000
| | P99| 49ms| 50ms | 1ms | 2.026
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 389ms| 382ms | -7ms | -1.799
| | P99| 984ms| 984ms | 0s | 0.000
| upsertDraft | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 15ms| 18ms | 3ms | 20.066
| viewChannel | Avg| 11ms| 13ms | 2ms | 17.397
| | P99| 25ms| 39ms | 14ms | 56.023
