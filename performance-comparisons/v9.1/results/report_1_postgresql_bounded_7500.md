### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.SearchGroupChannels | avg | 4ms | 13ms | 9ms | 214.88
| ChannelStore.AutocompleteInTeamForSearch | avg | 25ms | 59ms | 34ms | 136.06
| RoleStore.ChannelHigherScopedPermissions | avg | 6ms | 12ms | 6ms | 105.90
| ChannelStore.GetSidebarCategoriesForTeamForUser | avg | 20ms | 37ms | 17ms | 86.87
| ChannelStore.CreateInitialSidebarCategories | avg | 31ms | 54ms | 23ms | 75.32
| ChannelStore.GetSidebarCategory | avg | 11ms | 19ms | 8ms | 71.80
| ChannelStore.UpdateSidebarCategories | avg | 48ms | 74ms | 26ms | 54.51
| PreferenceStore.DeleteCategoryAndName | avg | 5ms | 7ms | 2ms | 44.23
| PreferenceStore.Save | avg | 13ms | 16ms | 3ms | 23.95
| ChannelStore.CreateDirectChannel | avg | 23ms | 25ms | 2ms | 8.57
| ChannelStore.GetMembers | avg | 124ms | 132ms | 8ms | 6.44
| ProductNoticesStore.View | avg | 59ms | 62ms | 3ms | 5.09
| ChannelStore.SaveMember | avg | 41ms | 43ms | 2ms | 4.92
| PostStore.SearchPostsForUser | avg | 172ms | 180ms | 8ms | 4.65
| UserStore.GetAllProfilesInChannel | avg | 295ms | 301ms | 6ms | 2.03
| PostStore.AnalyticsPostCount | avg | 804ms | 819ms | 15ms | 1.87
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| UserStore.GetMany | p99 | 5ms | 23ms | 18ms | 363.64
| RoleStore.ChannelHigherScopedPermissions | p99 | 24ms | 96ms | 72ms | 296.48
| UserStore.GetByUsername | p99 | 10ms | 36ms | 26ms | 268.33
| JobStore.UpdateStatus | p99 | 24ms | 77ms | 53ms | 224.39
| BotStore.Get | p99 | 10ms | 22ms | 12ms | 125.33
| PreferenceStore.DeleteCategoryAndName | p99 | 24ms | 48ms | 24ms | 101.48
| StatusStore.GetByIds | p99 | 24ms | 45ms | 21ms | 88.40
| StatusStore.UpdateExpiredDNDStatuses | p99 | 5ms | 9ms | 4ms | 80.81
| PostStore.GetPostReminderMetadata | p99 | 5ms | 9ms | 4ms | 80.77
| JobStore.Get | p99 | 23ms | 39ms | 16ms | 70.48
| PreferenceStore.Save | p99 | 97ms | 164ms | 67ms | 69.16
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 138ms | 208ms | 70ms | 50.71
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 21ms | 30ms | 9ms | 42.85
| ThreadStore.GetThreadUnreadReplyCount | p99 | 25ms | 35ms | 10ms | 40.40
| ChannelStore.SearchGroupChannels | p99 | 40ms | 56ms | 16ms | 39.86
| ThreadStore.GetTeamsUnreadForUser | p99 | 48ms | 67ms | 19ms | 39.25
| UserStore.GetUnreadCount | p99 | 33ms | 43ms | 10ms | 30.68
| PostStore.GetPostsByThread | p99 | 25ms | 32ms | 7ms | 28.36
| UserStore.AutocompleteUsersInChannel | p99 | 273ms | 344ms | 71ms | 26.02
| TeamStore.Get | p99 | 23ms | 29ms | 6ms | 25.80
| LinkMetadataStore.Get | p99 | 24ms | 30ms | 6ms | 25.12
| StatusStore.UpdateLastActivityAt | p99 | 27ms | 33ms | 6ms | 22.07
| ChannelStore.UpdateSidebarChannelsByPreferences | p99 | 19ms | 23ms | 4ms | 20.71
| PostStore.GetSingle | p99 | 22ms | 26ms | 4ms | 17.95
| FileInfoStore.Save | p99 | 41ms | 48ms | 7ms | 17.25
| UserStore.GetAllProfilesInChannel | p99 | 988ms | 1.156s | 168ms | 17.01
| ChannelStore.CreateInitialSidebarCategories | p99 | 235ms | 274ms | 39ms | 16.63
| JobStore.GetCountByStatusAndType | p99 | 38ms | 44ms | 6ms | 15.79
| PostStore.Save | p99 | 103ms | 117ms | 14ms | 13.58
| FileInfoStore.Get | p99 | 22ms | 25ms | 3ms | 13.48
| ChannelStore.SaveMember | p99 | 245ms | 278ms | 33ms | 13.48
| ChannelStore.CreateDirectChannel | p99 | 195ms | 221ms | 26ms | 13.34
| ThreadStore.MarkAsRead | p99 | 24ms | 27ms | 3ms | 12.71
| UserStore.IsEmpty | p99 | 24ms | 27ms | 3ms | 12.70
| PluginStore.Delete | p99 | 36ms | 40ms | 4ms | 11.14
| ChannelStore.GetGuestCount | p99 | 49ms | 54ms | 5ms | 10.16
| ChannelStore.GetChannels | p99 | 40ms | 44ms | 4ms | 10.03
| ThreadStore.MaintainMembership | p99 | 60ms | 66ms | 6ms | 9.94
| StatusStore.Get | p99 | 43ms | 47ms | 4ms | 9.36
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 43ms | 47ms | 4ms | 9.21
| PostStore.GetPostIdBeforeTime | p99 | 33ms | 36ms | 3ms | 9.15
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | p99 | 33ms | 36ms | 3ms | 8.99
| ChannelStore.GetMemberForPost | p99 | 24ms | 26ms | 2ms | 8.44
| SessionStore.Save | p99 | 84ms | 91ms | 7ms | 8.31
| WebhookStore.GetOutgoingByTeam | p99 | 49ms | 53ms | 4ms | 8.24
| PostAcknowledgementStore.GetForPosts | p99 | 39ms | 42ms | 3ms | 7.68
| ChannelStore.GetPinnedPostCount | p99 | 39ms | 42ms | 3ms | 7.61
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 41ms | 44ms | 3ms | 7.32
| ChannelStore.Get | p99 | 41ms | 44ms | 3ms | 7.25
| ThreadStore.GetTotalThreads | p99 | 43ms | 46ms | 3ms | 7.04
| ThreadStore.GetThreadFollowers | p99 | 29ms | 31ms | 2ms | 7.02
| ThreadStore.GetTotalUnreadMentions | p99 | 43ms | 46ms | 3ms | 6.98
| ThreadStore.GetTotalUnreadThreads | p99 | 43ms | 46ms | 3ms | 6.95
| UserStore.GetProfileByIds | p99 | 43ms | 46ms | 3ms | 6.91
| PostStore.GetPosts | p99 | 44ms | 47ms | 3ms | 6.77
| TeamStore.GetTeamsForUser | p99 | 44ms | 47ms | 3ms | 6.76
| TeamStore.GetTeamsByUserId | p99 | 45ms | 48ms | 3ms | 6.60
| TeamStore.GetAllPage | p99 | 45ms | 48ms | 3ms | 6.60
| SessionStore.UpdateLastActivityAt | p99 | 31ms | 33ms | 2ms | 6.56
| UserStore.GetForLogin | p99 | 46ms | 49ms | 3ms | 6.53
| GroupStore.GetByName | p99 | 46ms | 49ms | 3ms | 6.52
| ChannelStore.GetByName | p99 | 47ms | 50ms | 3ms | 6.33
| ChannelStore.GetFileCount | p99 | 34ms | 36ms | 2ms | 5.84
| ChannelStore.UpdateLastViewedAt | p99 | 35ms | 37ms | 2ms | 5.73
| UserStore.GetProfilesByUsernames | p99 | 36ms | 38ms | 2ms | 5.62
| GroupStore.GetGroups | p99 | 37ms | 39ms | 2ms | 5.44
| ChannelStore.GetSidebarCategory | p99 | 75ms | 79ms | 4ms | 5.33
| ReactionStore.Save | p99 | 95ms | 100ms | 5ms | 5.27
| PreferenceStore.Get | p99 | 38ms | 40ms | 2ms | 5.23
| ProductNoticesStore.View | p99 | 450ms | 473ms | 23ms | 5.11
| PostStore.GetPostsBefore | p99 | 40ms | 42ms | 2ms | 4.99
| ChannelStore.GetMembersForUser | p99 | 41ms | 43ms | 2ms | 4.90
| ChannelStore.IncrementMentionCount | p99 | 41ms | 43ms | 2ms | 4.88
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 41ms | 43ms | 2ms | 4.88
| PostPriorityStore.GetForPosts | p99 | 42ms | 44ms | 2ms | 4.74
| PostStore.GetPostIdAfterTime | p99 | 42ms | 44ms | 2ms | 4.71
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 45ms | 47ms | 2ms | 4.46
| UserTermsOfServiceStore.GetByUser | p99 | 45ms | 47ms | 2ms | 4.42
| PreferenceStore.GetAll | p99 | 47ms | 49ms | 2ms | 4.22
| SessionStore.Get | p99 | 92ms | 95ms | 3ms | 3.27
| TeamStore.SaveMember | p99 | 199ms | 205ms | 6ms | 3.02
| PostStore.GetPostsSince | p99 | 83ms | 85ms | 2ms | 2.41
| UserStore.Save | p99 | 241ms | 244ms | 3ms | 1.24
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| BotStore.Save | avg | 4ms | 0s | -4ms | -91.70
| StatusStore.SaveOrUpdate | avg | 53ms | 5ms | -48ms | -90.72
| SessionStore.GetSessionsExpired | avg | 6ms | 1ms | -5ms | -88.23
| PostStore.GetPostsAfter | avg | 6ms | 2ms | -4ms | -72.53
| SessionStore.Remove | avg | 9ms | 4ms | -5ms | -54.09
| LinkMetadataStore.Save | avg | 6ms | 4ms | -2ms | -35.17
| ChannelStore.GetTeamChannels | avg | 20ms | 13ms | -7ms | -34.20
| PostStore.SetPostReminder | avg | 10ms | 7ms | -3ms | -31.46
| ChannelStore.Save | avg | 16ms | 12ms | -4ms | -25.42
| ProductNoticesStore.ClearOldNotices | avg | 31ms | 27ms | -4ms | -12.95
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| BotStore.Save | p99 | 5ms | 0s | -5ms | -101.01
| StatusStore.SaveOrUpdate | p99 | 753ms | 42ms | -711ms | -94.46
| PostStore.GetPostsAfter | p99 | 87ms | 5ms | -82ms | -94.26
| SessionStore.GetSessionsExpired | p99 | 48ms | 5ms | -43ms | -89.12
| JobStore.UpdateStatusOptimistically | p99 | 44ms | 9ms | -35ms | -79.10
| SessionStore.Remove | p99 | 94ms | 23ms | -71ms | -75.14
| PostPersistentNotificationStore.DeleteExpired | p99 | 21ms | 9ms | -12ms | -58.11
| ChannelStore.GetChannelsByUser | p99 | 35ms | 15ms | -20ms | -57.96
| ThreadStore.Get | p99 | 31ms | 14ms | -17ms | -55.27
| ChannelStore.UpdateSidebarCategories | p99 | 212ms | 100ms | -112ms | -52.71
| PostStore.GetPostReminders | p99 | 46ms | 22ms | -24ms | -52.46
| ThreadStore.MarkAllAsReadByChannels | p99 | 10ms | 5ms | -5ms | -52.37
| ThreadStore.MarkAllAsReadByTeam | p99 | 10ms | 5ms | -5ms | -50.51
| ChannelStore.GetTeamChannels | p99 | 49ms | 25ms | -24ms | -48.67
| PostStore.Update | p99 | 81ms | 47ms | -34ms | -41.80
| ChannelStore.Save | p99 | 136ms | 85ms | -51ms | -37.51
| ChannelStore.Autocomplete | p99 | 160ms | 100ms | -60ms | -37.40
| ChannelStore.AutocompleteInTeamForSearch | p99 | 133ms | 95ms | -38ms | -28.48
| UserStore.Update | p99 | 94ms | 69ms | -25ms | -26.62
| FileInfoStore.SetContent | p99 | 84ms | 65ms | -19ms | -22.62
| PostAcknowledgementStore.GetForPost | p99 | 27ms | 22ms | -5ms | -18.35
| ChannelStore.GetChannelUnread | p99 | 23ms | 20ms | -3ms | -13.10
| FileInfoStore.AttachToPost | p99 | 64ms | 56ms | -8ms | -12.44
| PostPriorityStore.GetForPost | p99 | 26ms | 23ms | -3ms | -11.48
| FileInfoStore.GetForPost | p99 | 22ms | 20ms | -2ms | -9.16
| PostStore.Get | p99 | 67ms | 61ms | -6ms | -9.00
| ReactionStore.GetForPost | p99 | 33ms | 30ms | -3ms | -8.98
| PostPersistentNotificationStore.Get | p99 | 23ms | 21ms | -2ms | -8.76
| PostStore.SetPostReminder | p99 | 25ms | 23ms | -2ms | -8.13
| ChannelStore.GetPublicChannelsForTeam | p99 | 50ms | 46ms | -4ms | -8.05
| PluginStore.SetWithOptions | p99 | 78ms | 72ms | -6ms | -7.72
| ThreadStore.GetThreadForUser | p99 | 50ms | 48ms | -2ms | -4.02
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| searchGroupChannels | avg | 4ms | 13ms | 9ms | 211.45
| autocompleteChannelsForTeamForSearch | avg | 25ms | 59ms | 34ms | 135.72
| getCategoriesForTeamForUser | avg | 20ms | 37ms | 17ms | 85.32
| patchPost | avg | 250ms | 422ms | 172ms | 68.85
| updateCategoriesForTeamForUser | avg | 72ms | 114ms | 42ms | 58.33
| updateUserCustomStatus | avg | 191ms | 209ms | 18ms | 9.44
| login | avg | 84ms | 91ms | 7ms | 8.30
| getPostsForChannelAroundLastUnread | avg | 27ms | 29ms | 2ms | 7.49
| createGroupChannel | avg | 415ms | 443ms | 28ms | 6.74
| removeUserCustomStatus | avg | 210ms | 224ms | 14ms | 6.66
| addTeamMember | avg | 1.008s | 1.069s | 61ms | 6.05
| createUser | avg | 116ms | 123ms | 7ms | 6.03
| searchPostsInTeam | avg | 178ms | 188ms | 10ms | 5.61
| createPost | avg | 507ms | 525ms | 18ms | 3.55
| createDirectChannel | avg | 295ms | 303ms | 8ms | 2.72
| addChannelMember | avg | 280ms | 287ms | 7ms | 2.50
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| createDirectChannel | p99 | 497ms | 852ms | 355ms | 71.48
| getPostThread | p99 | 98ms | 141ms | 43ms | 43.96
| getCategoriesForTeamForUser | p99 | 150ms | 210ms | 60ms | 39.97
| searchGroupChannels | p99 | 41ms | 56ms | 15ms | 36.73
| autocompleteUsers | p99 | 229ms | 285ms | 56ms | 24.44
| login | p99 | 598ms | 727ms | 129ms | 21.59
| getChannelMember | p99 | 153ms | 183ms | 30ms | 19.63
| getAllTeams | p99 | 53ms | 63ms | 10ms | 18.79
| updatePreferences | p99 | 72ms | 85ms | 13ms | 18.15
| uploadFileStream | p99 | 1.318s | 1.556s | 238ms | 18.05
| viewChannel | p99 | 123ms | 140ms | 17ms | 13.87
| getClientConfig | p99 | 132ms | 149ms | 17ms | 12.83
| getPreferences | p99 | 49ms | 55ms | 6ms | 12.34
| updateReadStateThreadByUser | p99 | 226ms | 253ms | 27ms | 11.93
| getFileThumbnail | p99 | 130ms | 143ms | 13ms | 10.01
| getTeamsUnreadForUser | p99 | 81ms | 89ms | 8ms | 9.87
| getChannelMembersForTeamForUser | p99 | 45ms | 48ms | 3ms | 6.62
| getTeamsForUser | p99 | 46ms | 49ms | 3ms | 6.56
| getUser | p99 | 92ms | 98ms | 6ms | 6.50
| getUsersByNames | p99 | 37ms | 39ms | 2ms | 5.46
| getChannelStats | p99 | 79ms | 83ms | 4ms | 5.08
| saveReaction | p99 | 203ms | 213ms | 10ms | 4.91
| updateCategoriesForTeamForUser | p99 | 238ms | 249ms | 11ms | 4.63
| getThreadsForUser | p99 | 47ms | 49ms | 2ms | 4.26
| getChannelsForTeamForUser | p99 | 47ms | 49ms | 2ms | 4.21
| createUser | p99 | 465ms | 484ms | 19ms | 4.09
| getPostsForChannel | p99 | 245ms | 250ms | 5ms | 2.04
| addTeamMember | p99 | 4.374s | 4.458s | 84ms | 1.92
| getPostsForChannelAroundLastUnread | p99 | 244ms | 247ms | 3ms | 1.23
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getChannelMembers | avg | 9ms | 0s | -9ms | -98.72
| createChannel | avg | 21ms | 13ms | -8ms | -38.79
| followThreadByUser | avg | 23ms | 15ms | -8ms | -34.77
| logout | avg | 77ms | 54ms | -23ms | -29.92
| setPostReminder | avg | 20ms | 18ms | -2ms | -10.15
| getPublicChannelsForTeam | avg | 21ms | 19ms | -2ms | -9.69
| getProfileImage | avg | 106ms | 98ms | -8ms | -7.52
| getFilePreview | avg | 43ms | 41ms | -2ms | -4.69
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getChannelMembers | p99 | 10ms | 0s | -10ms | -100.50
| logout | p99 | 472ms | 99ms | -373ms | -78.95
| getChannelsForUser | p99 | 35ms | 15ms | -20ms | -57.96
| updateReadStateAllThreadsByUser | p99 | 10ms | 5ms | -5ms | -50.51
| followThreadByUser | p99 | 96ms | 48ms | -48ms | -50.26
| setPostReminder | p99 | 49ms | 25ms | -24ms | -49.35
| createChannel | p99 | 49ms | 25ms | -24ms | -48.67
| searchAllChannels | p99 | 160ms | 100ms | -60ms | -37.40
| getPublicChannelsForTeam | p99 | 73ms | 47ms | -26ms | -35.67
| autocompleteChannelsForTeamForSearch | p99 | 133ms | 95ms | -38ms | -28.48
| createPost | p99 | 3.086s | 2.474s | -612ms | -19.83
| getChannelUnread | p99 | 23ms | 20ms | -3ms | -13.10
| getFilePreview | p99 | 214ms | 210ms | -4ms | -1.87
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 6ms| 7ms | 1ms | 15.699
| |  P99| 48ms| 49ms | 1ms | 2.087
| BotStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 22ms | 12ms | 125.326
| BotStore.Save |  Avg| 4ms| 0s | -4ms | -91.704
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 5ms| 6ms | 1ms | 18.332
| |  P99| 41ms| 44ms | 3ms | 7.318
| ChannelStore.Autocomplete |  Avg| 46ms| 45ms | -1ms | -2.161
| |  P99| 160ms| 100ms | -60ms | -37.403
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 25ms| 59ms | 34ms | 136.064
| |  P99| 133ms| 95ms | -38ms | -28.478
| ChannelStore.CreateDirectChannel |  Avg| 23ms| 25ms | 2ms | 8.574
| |  P99| 195ms| 221ms | 26ms | 13.341
| ChannelStore.CreateInitialSidebarCategories |  Avg| 31ms| 54ms | 23ms | 75.323
| |  P99| 235ms| 274ms | 39ms | 16.630
| ChannelStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 41ms| 44ms | 3ms | 7.253
| ChannelStore.GetAllChannelMembersForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 20ms| 21ms | 1ms | 5.004
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 29ms| 29ms | 0s | 0.000
| |  P99| 189ms| 188ms | -1ms | -0.530
| ChannelStore.GetByName |  Avg| 5ms| 6ms | 1ms | 18.840
| |  P99| 47ms| 50ms | 3ms | 6.334
| ChannelStore.GetChannelUnread |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 23ms| 20ms | -3ms | -13.101
| ChannelStore.GetChannels |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 40ms| 44ms | 4ms | 10.031
| ChannelStore.GetChannelsByUser |  Avg| 3ms| 2ms | -1ms | -28.634
| |  P99| 35ms| 15ms | -20ms | -57.964
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 33ms| 36ms | 3ms | 8.993
| ChannelStore.GetFileCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 34ms| 36ms | 2ms | 5.842
| ChannelStore.GetGuestCount |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 49ms| 54ms | 5ms | 10.157
| ChannelStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 21ms| 22ms | 1ms | 4.784
| ChannelStore.GetMemberCount |  Avg| 23ms| 24ms | 1ms | 4.359
| |  P99| 95ms| 96ms | 1ms | 1.058
| ChannelStore.GetMemberForPost |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 24ms| 26ms | 2ms | 8.441
| ChannelStore.GetMembers |  Avg| 124ms| 132ms | 8ms | 6.437
| |  P99| 492ms| 494ms | 2ms | 0.406
| ChannelStore.GetMembersForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 41ms| 43ms | 2ms | 4.903
| ChannelStore.GetPinnedPostCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 39ms| 42ms | 3ms | 7.615
| ChannelStore.GetPublicChannelsForTeam |  Avg| 19ms| 18ms | -1ms | -5.220
| |  P99| 50ms| 46ms | -4ms | -8.050
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 20ms| 37ms | 17ms | 86.867
| |  P99| 138ms| 208ms | 70ms | 50.713
| ChannelStore.GetSidebarCategory |  Avg| 11ms| 19ms | 8ms | 71.805
| |  P99| 75ms| 79ms | 4ms | 5.334
| ChannelStore.GetTeamChannels |  Avg| 20ms| 13ms | -7ms | -34.201
| |  P99| 49ms| 25ms | -24ms | -48.669
| ChannelStore.IncrementMentionCount |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 41ms| 43ms | 2ms | 4.883
| ChannelStore.InvalidateAllChannelMembersForUser |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.InvalidateChannelByName |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.Save |  Avg| 16ms| 12ms | -4ms | -25.424
| |  P99| 136ms| 85ms | -51ms | -37.509
| ChannelStore.SaveMember |  Avg| 41ms| 43ms | 2ms | 4.919
| |  P99| 245ms| 278ms | 33ms | 13.477
| ChannelStore.SearchGroupChannels |  Avg| 4ms| 13ms | 9ms | 214.877
| |  P99| 40ms| 56ms | 16ms | 39.864
| ChannelStore.UpdateLastViewedAt |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 35ms| 37ms | 2ms | 5.733
| ChannelStore.UpdateSidebarCategories |  Avg| 48ms| 74ms | 26ms | 54.509
| |  P99| 212ms| 100ms | -112ms | -52.708
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 23ms | 4ms | 20.711
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 56ms| 55ms | -1ms | -1.801
| CommandWebhookStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.AttachToPost |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 64ms| 56ms | -8ms | -12.443
| FileInfoStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 22ms| 25ms | 3ms | 13.483
| FileInfoStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 22ms| 20ms | -2ms | -9.156
| FileInfoStore.Save |  Avg| 6ms| 7ms | 1ms | 15.580
| |  P99| 41ms| 48ms | 7ms | 17.252
| FileInfoStore.SetContent |  Avg| 11ms| 10ms | -1ms | -9.355
| |  P99| 84ms| 65ms | -19ms | -22.618
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 41ms| 43ms | 2ms | 4.877
| GroupStore.GetByName |  Avg| 3ms| 4ms | 1ms | 29.596
| |  P99| 46ms| 49ms | 3ms | 6.525
| GroupStore.GetGroups |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 37ms| 39ms | 2ms | 5.445
| JobStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 23ms| 39ms | 16ms | 70.485
| JobStore.GetAllByStatus |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 48ms| 48ms | 0s | 0.000
| JobStore.GetCountByStatusAndType |  Avg| 2ms| 3ms | 1ms | 48.645
| |  P99| 38ms| 44ms | 6ms | 15.789
| JobStore.GetNewestJobByStatusesAndType |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 26ms| 25ms | -1ms | -3.846
| JobStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 21ms| 21ms | 0s | 0.000
| JobStore.UpdateOptimistically |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 39ms| 39ms | 0s | 0.000
| JobStore.UpdateStatus |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 24ms| 77ms | 53ms | 224.386
| JobStore.UpdateStatusOptimistically |  Avg| 5ms| 4ms | -1ms | -18.265
| |  P99| 44ms| 9ms | -35ms | -79.096
| LinkMetadataStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 24ms| 30ms | 6ms | 25.121
| LinkMetadataStore.Save |  Avg| 6ms| 4ms | -2ms | -35.174
| |  P99| 23ms| 22ms | -1ms | -4.255
| PluginStore.Delete |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 36ms| 40ms | 4ms | 11.143
| PluginStore.List |  Avg| 2ms| 3ms | 1ms | 42.491
| |  P99| 41ms| 41ms | 0s | 0.000
| PluginStore.SetWithOptions |  Avg| 9ms| 8ms | -1ms | -11.358
| |  P99| 78ms| 72ms | -6ms | -7.724
| PostAcknowledgementStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 27ms| 22ms | -5ms | -18.349
| PostAcknowledgementStore.GetForPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 39ms| 42ms | 3ms | 7.681
| PostPersistentNotificationStore.DeleteExpired |  Avg| 3ms| 2ms | -1ms | -39.809
| |  P99| 21ms| 9ms | -12ms | -58.111
| PostPersistentNotificationStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 21ms | -2ms | -8.762
| PostPersistentNotificationStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| PostPriorityStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 26ms| 23ms | -3ms | -11.483
| PostPriorityStore.GetForPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 42ms| 44ms | 2ms | 4.737
| PostStore.AnalyticsPostCount |  Avg| 804ms| 819ms | 15ms | 1.866
| |  P99| 995ms| 995ms | 0s | 0.000
| PostStore.Delete |  Avg| 14ms| 13ms | -1ms | -7.346
| |  P99| 25ms| 25ms | 0s | 0.000
| PostStore.Get |  Avg| 6ms| 5ms | -1ms | -17.730
| |  P99| 67ms| 61ms | -6ms | -8.999
| PostStore.GetEtag |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 45ms| 46ms | 1ms | 2.201
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 42ms| 44ms | 2ms | 4.713
| PostStore.GetPostIdBeforeTime |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 33ms| 36ms | 3ms | 9.146
| PostStore.GetPostReminderMetadata |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.766
| PostStore.GetPostReminders |  Avg| 8ms| 7ms | -1ms | -13.199
| |  P99| 46ms| 22ms | -24ms | -52.459
| PostStore.GetPosts |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 44ms| 47ms | 3ms | 6.774
| PostStore.GetPostsAfter |  Avg| 6ms| 2ms | -4ms | -72.528
| |  P99| 87ms| 5ms | -82ms | -94.255
| PostStore.GetPostsBefore |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 40ms| 42ms | 2ms | 4.991
| PostStore.GetPostsByThread |  Avg| 4ms| 5ms | 1ms | 22.917
| |  P99| 25ms| 32ms | 7ms | 28.357
| PostStore.GetPostsSince |  Avg| 11ms| 12ms | 1ms | 8.740
| |  P99| 83ms| 85ms | 2ms | 2.409
| PostStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 22ms| 26ms | 4ms | 17.945
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 16ms| 16ms | 0s | 0.000
| |  P99| 103ms| 117ms | 14ms | 13.577
| PostStore.SearchPostsForUser |  Avg| 172ms| 180ms | 8ms | 4.653
| |  P99| 2.347s| 2.354s | 7ms | 0.298
| PostStore.SetPostReminder |  Avg| 10ms| 7ms | -3ms | -31.462
| |  P99| 25ms| 23ms | -2ms | -8.134
| PostStore.Update |  Avg| 16ms| 15ms | -1ms | -6.133
| |  P99| 81ms| 47ms | -34ms | -41.803
| PreferenceStore.DeleteCategoryAndName |  Avg| 5ms| 7ms | 2ms | 44.234
| |  P99| 24ms| 48ms | 24ms | 101.482
| PreferenceStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 38ms| 40ms | 2ms | 5.231
| PreferenceStore.GetAll |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 47ms| 49ms | 2ms | 4.224
| PreferenceStore.Save |  Avg| 13ms| 16ms | 3ms | 23.952
| |  P99| 97ms| 164ms | 67ms | 69.161
| ProductNoticesStore.ClearOldNotices |  Avg| 31ms| 27ms | -4ms | -12.948
| |  P99| 50ms| 50ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 59ms| 62ms | 3ms | 5.090
| |  P99| 450ms| 473ms | 23ms | 5.113
| ReactionStore.GetForPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 33ms| 30ms | -3ms | -8.982
| ReactionStore.Save |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 95ms| 100ms | 5ms | 5.268
| RoleStore.ChannelHigherScopedPermissions |  Avg| 6ms| 12ms | 6ms | 105.899
| |  P99| 24ms| 96ms | 72ms | 296.485
| RoleStore.GetByNames |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Get |  Avg| 9ms| 10ms | 1ms | 10.618
| |  P99| 92ms| 95ms | 3ms | 3.272
| SessionStore.GetSessionsExpired |  Avg| 6ms| 1ms | -5ms | -88.231
| |  P99| 48ms| 5ms | -43ms | -89.119
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 21ms| 30ms | 9ms | 42.854
| SessionStore.Remove |  Avg| 9ms| 4ms | -5ms | -54.089
| |  P99| 94ms| 23ms | -71ms | -75.136
| SessionStore.Save |  Avg| 9ms| 10ms | 1ms | 10.551
| |  P99| 84ms| 91ms | 7ms | 8.308
| SessionStore.UpdateLastActivityAt |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 31ms| 33ms | 2ms | 6.557
| StatusStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 43ms| 47ms | 4ms | 9.357
| StatusStore.GetByIds |  Avg| 2ms| 3ms | 1ms | 42.277
| |  P99| 24ms| 45ms | 21ms | 88.398
| StatusStore.SaveOrUpdate |  Avg| 53ms| 5ms | -48ms | -90.719
| |  P99| 753ms| 42ms | -711ms | -94.462
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.808
| StatusStore.UpdateLastActivityAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 27ms| 33ms | 6ms | 22.070
| SystemStore.GetByName |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 45ms| 46ms | 1ms | 2.217
| TeamStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 23ms| 29ms | 6ms | 25.797
| TeamStore.GetAllPage |  Avg| 3ms| 4ms | 1ms | 30.170
| |  P99| 45ms| 48ms | 3ms | 6.596
| TeamStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 30ms| 31ms | 1ms | 3.375
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 45ms| 47ms | 2ms | 4.458
| TeamStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.190
| TeamStore.GetTeamsByUserId |  Avg| 3ms| 4ms | 1ms | 29.052
| |  P99| 45ms| 48ms | 3ms | 6.604
| TeamStore.GetTeamsForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 44ms| 47ms | 3ms | 6.758
| TeamStore.SaveMember |  Avg| 34ms| 35ms | 1ms | 2.935
| |  P99| 199ms| 205ms | 6ms | 3.017
| ThreadStore.Get |  Avg| 2ms| 1ms | -1ms | -63.781
| |  P99| 31ms| 14ms | -17ms | -55.273
| ThreadStore.GetMembershipForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 32ms| 31ms | -1ms | -3.083
| ThreadStore.GetTeamsUnreadForUser |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 48ms| 67ms | 19ms | 39.248
| ThreadStore.GetThreadFollowers |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 29ms| 31ms | 2ms | 7.017
| ThreadStore.GetThreadForUser |  Avg| 6ms| 5ms | -1ms | -17.954
| |  P99| 50ms| 48ms | -2ms | -4.025
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 25ms| 35ms | 10ms | 40.396
| ThreadStore.GetThreadsForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 42ms| 42ms | 0s | 0.000
| ThreadStore.GetTotalThreads |  Avg| 3ms| 4ms | 1ms | 29.857
| |  P99| 43ms| 46ms | 3ms | 7.041
| ThreadStore.GetTotalUnreadMentions |  Avg| 3ms| 4ms | 1ms | 30.764
| |  P99| 43ms| 46ms | 3ms | 6.981
| ThreadStore.GetTotalUnreadThreads |  Avg| 3ms| 4ms | 1ms | 29.057
| |  P99| 43ms| 46ms | 3ms | 6.951
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 43ms| 47ms | 4ms | 9.214
| ThreadStore.MaintainMembership |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 60ms| 66ms | 6ms | 9.935
| ThreadStore.MarkAllAsReadByChannels |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 5ms | -5ms | -52.370
| ThreadStore.MarkAllAsReadByTeam |  Avg| 5ms| 4ms | -1ms | -21.703
| |  P99| 10ms| 5ms | -5ms | -50.505
| ThreadStore.MarkAsRead |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 24ms| 27ms | 3ms | 12.708
| ThreadStore.UpdateMembership |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 23ms| 24ms | 1ms | 4.397
| TokenStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AutocompleteUsersInChannel |  Avg| 49ms| 50ms | 1ms | 2.024
| |  P99| 273ms| 344ms | 71ms | 26.019
| UserStore.Count |  Avg| 14ms| 13ms | -1ms | -6.918
| |  P99| 48ms| 47ms | -1ms | -2.094
| UserStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| UserStore.GetAllProfiles |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 37ms| 38ms | 1ms | 2.739
| UserStore.GetAllProfilesInChannel |  Avg| 295ms| 301ms | 6ms | 2.032
| |  P99| 988ms| 1.156s | 168ms | 17.010
| UserStore.GetByUsername |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 36ms | 26ms | 268.331
| UserStore.GetForLogin |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 46ms| 49ms | 3ms | 6.531
| UserStore.GetMany |  Avg| 1ms| 2ms | 1ms | 78.406
| |  P99| 5ms| 23ms | 18ms | 363.636
| UserStore.GetProfileByIds |  Avg| 3ms| 4ms | 1ms | 29.565
| |  P99| 43ms| 46ms | 3ms | 6.907
| UserStore.GetProfilesByUsernames |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 36ms| 38ms | 2ms | 5.616
| UserStore.GetUnreadCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 33ms| 43ms | 10ms | 30.679
| UserStore.IsEmpty |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 24ms| 27ms | 3ms | 12.696
| UserStore.Save |  Avg| 79ms| 79ms | 0s | 0.000
| |  P99| 241ms| 244ms | 3ms | 1.243
| UserStore.Search |  Avg| 19ms| 19ms | 0s | 0.000
| |  P99| 98ms| 99ms | 1ms | 1.016
| UserStore.Update |  Avg| 11ms| 10ms | -1ms | -9.400
| |  P99| 94ms| 69ms | -25ms | -26.620
| UserStore.UpdateFailedPasswordAttempts |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 49ms| 50ms | 1ms | 2.022
| UserStore.UpdateUpdateAt |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 45ms| 44ms | -1ms | -2.220
| UserTermsOfServiceStore.GetByUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 45ms| 47ms | 2ms | 4.419
| WebhookStore.GetOutgoingByTeam |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 49ms| 53ms | 4ms | 8.241
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 280ms| 287ms | 7ms | 2.500
| | P99| 950ms| 947ms | -3ms | -0.316
| addTeamMember | Avg| 1.008s| 1.069s | 61ms | 6.053
| | P99| 4.374s| 4.458s | 84ms | 1.921
| autocompleteChannelsForTeamForSearch | Avg| 25ms| 59ms | 34ms | 135.724
| | P99| 133ms| 95ms | -38ms | -28.478
| autocompleteUsers | Avg| 40ms| 41ms | 1ms | 2.504
| | P99| 229ms| 285ms | 56ms | 24.437
| createChannel | Avg| 21ms| 13ms | -8ms | -38.787
| | P99| 49ms| 25ms | -24ms | -48.669
| createDirectChannel | Avg| 295ms| 303ms | 8ms | 2.716
| | P99| 497ms| 852ms | 355ms | 71.477
| createGroupChannel | Avg| 415ms| 443ms | 28ms | 6.739
| | P99| 980ms| 983ms | 3ms | 0.306
| createPost | Avg| 507ms| 525ms | 18ms | 3.549
| | P99| 3.086s| 2.474s | -612ms | -19.832
| createUser | Avg| 116ms| 123ms | 7ms | 6.025
| | P99| 465ms| 484ms | 19ms | 4.088
| deletePost | Avg| 18ms| 18ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| followThreadByUser | Avg| 23ms| 15ms | -8ms | -34.771
| | P99| 96ms| 48ms | -48ms | -50.261
| getAllTeams | Avg| 4ms| 5ms | 1ms | 23.236
| | P99| 53ms| 63ms | 10ms | 18.788
| getCategoriesForTeamForUser | Avg| 20ms| 37ms | 17ms | 85.319
| | P99| 150ms| 210ms | 60ms | 39.972
| getChannel | Avg| 6ms| 5ms | -1ms | -17.614
| | P99| 48ms| 47ms | -1ms | -2.075
| getChannelMember | Avg| 13ms| 14ms | 1ms | 7.652
| | P99| 153ms| 183ms | 30ms | 19.626
| getChannelMembers | Avg| 9ms| 0s | -9ms | -98.716
| | P99| 10ms| 0s | -10ms | -100.503
| getChannelMembersForTeamForUser | Avg| 4ms| 5ms | 1ms | 23.138
| | P99| 45ms| 48ms | 3ms | 6.625
| getChannelStats | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 79ms| 83ms | 4ms | 5.077
| getChannelUnread | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 23ms| 20ms | -3ms | -13.101
| getChannelsForTeamForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 47ms| 49ms | 2ms | 4.214
| getChannelsForUser | Avg| 4ms| 3ms | -1ms | -28.124
| | P99| 35ms| 15ms | -20ms | -57.964
| getClientConfig | Avg| 12ms| 12ms | 0s | 0.000
| | P99| 132ms| 149ms | 17ms | 12.832
| getFilePreview | Avg| 43ms| 41ms | -2ms | -4.691
| | P99| 214ms| 210ms | -4ms | -1.869
| getFileThumbnail | Avg| 34ms| 34ms | 0s | 0.000
| | P99| 130ms| 143ms | 13ms | 10.014
| getPostThread | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 98ms| 141ms | 43ms | 43.956
| getPostsForChannel | Avg| 29ms| 29ms | 0s | 0.000
| | P99| 245ms| 250ms | 5ms | 2.039
| getPostsForChannelAroundLastUnread | Avg| 27ms| 29ms | 2ms | 7.489
| | P99| 244ms| 247ms | 3ms | 1.229
| getPreferences | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 49ms| 55ms | 6ms | 12.336
| getProfileImage | Avg| 106ms| 98ms | -8ms | -7.515
| | P99| 489ms| 485ms | -4ms | -0.818
| getPublicChannelsForTeam | Avg| 21ms| 19ms | -2ms | -9.695
| | P99| 73ms| 47ms | -26ms | -35.672
| getTeamMember | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 44ms| 45ms | 1ms | 2.282
| getTeamMembersForUser | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 69ms| 68ms | -1ms | -1.448
| getTeamsForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 46ms| 49ms | 3ms | 6.558
| getTeamsUnreadForUser | Avg| 6ms| 7ms | 1ms | 15.444
| | P99| 81ms| 89ms | 8ms | 9.868
| getThreadsForUser | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 47ms| 49ms | 2ms | 4.256
| getUser | Avg| 6ms| 7ms | 1ms | 17.396
| | P99| 92ms| 98ms | 6ms | 6.503
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 96ms| 97ms | 1ms | 1.045
| getUsersByIds | Avg| 2ms| 1ms | -1ms | -64.840
| | P99| 11ms| 10ms | -1ms | -8.747
| getUsersByNames | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 37ms| 39ms | 2ms | 5.461
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| login | Avg| 84ms| 91ms | 7ms | 8.297
| | P99| 598ms| 727ms | 129ms | 21.586
| logout | Avg| 77ms| 54ms | -23ms | -29.919
| | P99| 472ms| 99ms | -373ms | -78.945
| patchPost | Avg| 250ms| 422ms | 172ms | 68.846
| | P99| 10s| 10s | 0s | 0.000
| removeUserCustomStatus | Avg| 210ms| 224ms | 14ms | 6.662
| | P99| 493ms| 492ms | -1ms | -0.203
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 25ms| 25ms | 0s | 0.000
| | P99| 203ms| 213ms | 10ms | 4.915
| searchAllChannels | Avg| 47ms| 46ms | -1ms | -2.149
| | P99| 160ms| 100ms | -60ms | -37.403
| searchGroupChannels | Avg| 4ms| 13ms | 9ms | 211.454
| | P99| 41ms| 56ms | 15ms | 36.728
| searchPostsInTeam | Avg| 178ms| 188ms | 10ms | 5.611
| | P99| 2.359s| 2.37s | 11ms | 0.466
| searchUsers | Avg| 20ms| 20ms | 0s | 0.000
| | P99| 99ms| 99ms | 0s | 0.000
| setPostReminder | Avg| 20ms| 18ms | -2ms | -10.147
| | P99| 49ms| 25ms | -24ms | -49.354
| unfollowThreadByUser | Avg| 14ms| 13ms | -1ms | -7.118
| | P99| 67ms| 68ms | 1ms | 1.492
| updateCategoriesForTeamForUser | Avg| 72ms| 114ms | 42ms | 58.330
| | P99| 238ms| 249ms | 11ms | 4.632
| updatePreferences | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 72ms| 85ms | 13ms | 18.148
| updateReadStateAllThreadsByUser | Avg| 5ms| 4ms | -1ms | -21.293
| | P99| 10ms| 5ms | -5ms | -50.505
| updateReadStateThreadByUser | Avg| 40ms| 41ms | 1ms | 2.531
| | P99| 226ms| 253ms | 27ms | 11.926
| updateUserCustomStatus | Avg| 191ms| 209ms | 18ms | 9.444
| | P99| 491ms| 489ms | -2ms | -0.407
| uploadFileStream | Avg| 434ms| 430ms | -4ms | -0.921
| | P99| 1.318s| 1.556s | 238ms | 18.051
| viewChannel | Avg| 12ms| 12ms | 0s | 0.000
| | P99| 123ms| 140ms | 17ms | 13.866
