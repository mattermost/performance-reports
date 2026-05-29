### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostStore.AnalyticsPostCount | avg | 2ms | 138ms | 136ms | 6306.66
| ChannelStore.GetMemberForPost | avg | 4ms | 20ms | 16ms | 388.12
| PostStore.SearchPostsForUser | avg | 29ms | 107ms | 78ms | 271.84
| PostStore.GetPostReminderMetadata | avg | 2ms | 5ms | 3ms | 126.18
| ChannelStore.GetForPost | avg | 2ms | 4ms | 2ms | 90.14
| StatusStore.SaveOrUpdateMany | avg | 7ms | 9ms | 2ms | 27.79
| ChannelStore.GetTeamChannels | avg | 17ms | 20ms | 3ms | 17.65
| PostStore.Update | avg | 12ms | 14ms | 2ms | 16.67
| UserStore.GetAllProfilesInChannel | avg | 148ms | 152ms | 4ms | 2.70
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostStore.AnalyticsPostCount | p99 | 5ms | 495ms | 490ms | 9895.43
| PostStore.SetPostReminder | p99 | 10ms | 24ms | 14ms | 140.70
| PostPersistentNotificationStore.Get | p99 | 9ms | 21ms | 12ms | 140.35
| ChannelStore.GetMemberForPost | p99 | 16ms | 35ms | 19ms | 121.78
| JobStore.UpdateOptimistically | p99 | 7ms | 15ms | 8ms | 109.59
| PostStore.GetPostReminderMetadata | p99 | 5ms | 10ms | 5ms | 100.96
| PostStore.Update | p99 | 25ms | 50ms | 25ms | 100.62
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 82ms | 160ms | 78ms | 95.59
| ScheduledPostStore.GetPendingScheduledPosts | p99 | 5ms | 9ms | 4ms | 80.81
| UserStore.GetMany | p99 | 5ms | 9ms | 4ms | 80.81
| StatusStore.SaveOrUpdateMany | p99 | 25ms | 43ms | 18ms | 72.56
| RoleStore.ChannelHigherScopedPermissions | p99 | 5ms | 8ms | 3ms | 60.61
| EmojiStore.GetByName | p99 | 5ms | 8ms | 3ms | 57.16
| PostStore.SearchPostsForUser | p99 | 670ms | 964ms | 294ms | 43.88
| ChannelStore.CreateDirectChannel | p99 | 50ms | 64ms | 14ms | 28.17
| ChannelStore.GetPublicChannelsForTeam | p99 | 25ms | 28ms | 3ms | 12.00
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelBookmarkStore.Get | avg | 2ms | 0s | -2ms | -117.64
| SchemeStore.GetAllPage | avg | 2ms | 0s | -2ms | -117.17
| ChannelStore.CreateSidebarCategory | avg | 20ms | 0s | -20ms | -100.02
| ChannelBookmarkStore.Delete | avg | 8ms | 0s | -8ms | -95.72
| ChannelStore.AutocompleteInTeamForSearch | avg | 48ms | 39ms | -9ms | -18.56
| ChannelStore.Autocomplete | avg | 37ms | 34ms | -3ms | -8.09
| ProductNoticesStore.View | avg | 44ms | 41ms | -3ms | -6.85
| UserStore.Save | avg | 124ms | 121ms | -3ms | -2.42
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| SchemeStore.GetAllPage | p99 | 5ms | 0s | -5ms | -101.01
| RetentionPolicyStore.GetCount | p99 | 5ms | 0s | -5ms | -101.01
| RetentionPolicyStore.GetAll | p99 | 5ms | 0s | -5ms | -101.01
| ChannelBookmarkStore.Get | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.CreateSidebarCategory | p99 | 25ms | 0s | -25ms | -100.60
| ChannelBookmarkStore.Delete | p99 | 10ms | 0s | -10ms | -100.50
| RoleStore.GetByNames | p99 | 21ms | 5ms | -16ms | -76.92
| JobStore.Save | p99 | 21ms | 5ms | -16ms | -75.56
| LinkMetadataStore.Save | p99 | 21ms | 6ms | -15ms | -72.11
| StatusStore.UpdateExpiredDNDStatuses | p99 | 28ms | 8ms | -20ms | -72.07
| DraftStore.GetDraftsForUser | p99 | 18ms | 7ms | -11ms | -61.99
| UserStore.GetProfilesInChannel | p99 | 25ms | 10ms | -15ms | -60.73
| ChannelStore.Autocomplete | p99 | 251ms | 100ms | -151ms | -60.25
| PostStore.GetPostReminders | p99 | 22ms | 9ms | -13ms | -57.91
| PostStore.GetPostsByThread | p99 | 22ms | 10ms | -12ms | -55.77
| ClusterDiscoveryStore.SetLastPingAt | p99 | 24ms | 11ms | -13ms | -55.23
| JobStore.GetAllByStatus | p99 | 17ms | 9ms | -8ms | -48.27
| ChannelStore.GetChannelUnread | p99 | 9ms | 5ms | -4ms | -47.06
| FileInfoStore.Save | p99 | 19ms | 10ms | -9ms | -46.30
| FileInfoStore.AttachToPost | p99 | 22ms | 12ms | -10ms | -44.78
| ChannelStore.GetFileCount | p99 | 9ms | 5ms | -4ms | -44.16
| ChannelStore.UpdateSidebarCategories | p99 | 89ms | 50ms | -39ms | -44.00
| BotStore.Get | p99 | 9ms | 5ms | -4ms | -43.48
| PropertyValueStore.SearchPropertyValues | p99 | 12ms | 7ms | -5ms | -43.34
| PreferenceStore.DeleteCategoryAndName | p99 | 9ms | 5ms | -4ms | -43.01
| FileInfoStore.SetContent | p99 | 23ms | 14ms | -9ms | -39.71
| ChannelStore.GetMembersForUser | p99 | 16ms | 10ms | -6ms | -38.12
| ChannelStore.GetByName | p99 | 38ms | 25ms | -13ms | -34.55
| UserStore.IsEmpty | p99 | 15ms | 10ms | -5ms | -33.33
| ChannelStore.GetChannels | p99 | 14ms | 10ms | -4ms | -29.45
| PostPersistentNotificationStore.GetSingle | p99 | 7ms | 5ms | -2ms | -27.36
| WebhookStore.GetOutgoingByTeam | p99 | 22ms | 16ms | -6ms | -27.18
| DraftStore.Delete | p99 | 7ms | 5ms | -2ms | -26.86
| UserStore.GetProfilesByUsernames | p99 | 8ms | 6ms | -2ms | -25.88
| UserStore.UpdateFailedPasswordAttempts | p99 | 31ms | 23ms | -8ms | -25.72
| PostStore.GetPostIdAfterTime | p99 | 20ms | 15ms | -5ms | -25.05
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | p99 | 8ms | 6ms | -2ms | -24.47
| ChannelStore.GetMemberLastViewedAt | p99 | 21ms | 16ms | -5ms | -24.03
| UserStore.Get | p99 | 17ms | 13ms | -4ms | -22.92
| SessionStore.Save | p99 | 41ms | 32ms | -9ms | -21.75
| ChannelStore.IncrementMentionCount | p99 | 19ms | 15ms | -4ms | -21.42
| ChannelStore.Get | p99 | 19ms | 15ms | -4ms | -21.32
| ChannelStore.SaveMember | p99 | 122ms | 97ms | -25ms | -20.50
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 20ms | 16ms | -4ms | -20.31
| StatusStore.Get | p99 | 20ms | 16ms | -4ms | -20.15
| ThreadStore.GetTotalThreads | p99 | 20ms | 16ms | -4ms | -19.96
| ChannelStore.Save | p99 | 41ms | 33ms | -8ms | -19.39
| PropertyFieldStore.SearchPropertyFields | p99 | 21ms | 17ms | -4ms | -19.21
| PostAcknowledgementStore.GetForPosts | p99 | 12ms | 10ms | -2ms | -17.33
| ThreadStore.GetThreadForUser | p99 | 24ms | 20ms | -4ms | -16.80
| UserStore.GetProfileByIds | p99 | 18ms | 15ms | -3ms | -16.42
| ThreadStore.GetTotalUnreadMentions | p99 | 19ms | 16ms | -3ms | -16.07
| ProductNoticesStore.View | p99 | 196ms | 165ms | -31ms | -15.84
| ThreadStore.GetTotalUnreadThreads | p99 | 20ms | 17ms | -3ms | -15.16
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 20ms | 17ms | -3ms | -14.91
| PreferenceStore.Save | p99 | 55ms | 47ms | -8ms | -14.47
| PropertyGroupStore.Get | p99 | 21ms | 18ms | -3ms | -14.28
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 35ms | 30ms | -5ms | -14.10
| TeamStore.GetMember | p99 | 21ms | 18ms | -3ms | -14.01
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 22ms | 19ms | -3ms | -13.94
| ChannelStore.AutocompleteInTeamForSearch | p99 | 244ms | 210ms | -34ms | -13.93
| UserStore.GetForLogin | p99 | 22ms | 19ms | -3ms | -13.71
| SystemStore.GetByName | p99 | 22ms | 19ms | -3ms | -13.71
| SessionStore.GetLRUSessions | p99 | 22ms | 19ms | -3ms | -13.59
| PostStore.GetPosts | p99 | 22ms | 19ms | -3ms | -13.58
| ChannelStore.GetAllChannelMembersForUser | p99 | 22ms | 19ms | -3ms | -13.48
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 22ms | 19ms | -3ms | -13.41
| TeamStore.GetTeamsByUserId | p99 | 23ms | 20ms | -3ms | -13.33
| TeamStore.GetTeamsForUser | p99 | 23ms | 20ms | -3ms | -13.32
| ChannelStore.GetChannelsByUser | p99 | 23ms | 20ms | -3ms | -13.30
| GroupStore.GetGroups | p99 | 15ms | 13ms | -2ms | -13.23
| ChannelStore.GetMember | p99 | 23ms | 20ms | -3ms | -12.82
| ThreadStore.GetTeamsUnreadForUser | p99 | 24ms | 21ms | -3ms | -12.76
| ThreadStore.GetThreadUnreadReplyCount | p99 | 24ms | 21ms | -3ms | -12.63
| PostStore.GetEtag | p99 | 16ms | 14ms | -2ms | -12.39
| TeamStore.SaveMember | p99 | 82ms | 72ms | -10ms | -12.17
| SessionStore.Get | p99 | 42ms | 37ms | -5ms | -11.95
| ChannelStore.CreateInitialSidebarCategories | p99 | 76ms | 68ms | -8ms | -10.54
| UserStore.GetAllProfiles | p99 | 20ms | 18ms | -2ms | -9.89
| ScheduledPostStore.GetScheduledPostsForUser | p99 | 21ms | 19ms | -2ms | -9.47
| UserTermsOfServiceStore.GetByUser | p99 | 22ms | 20ms | -2ms | -9.20
| ThreadStore.MaintainMembership | p99 | 22ms | 20ms | -2ms | -8.99
| TeamStore.GetAllPage | p99 | 22ms | 20ms | -2ms | -8.91
| UserStore.Count | p99 | 47ms | 43ms | -4ms | -8.58
| UserStore.UpdateUpdateAt | p99 | 23ms | 21ms | -2ms | -8.55
| UserStore.UpdateLastLogin | p99 | 23ms | 21ms | -2ms | -8.55
| PostStore.Get | p99 | 24ms | 22ms | -2ms | -8.44
| GroupStore.GetByName | p99 | 24ms | 22ms | -2ms | -8.38
| PreferenceStore.GetAll | p99 | 24ms | 22ms | -2ms | -8.22
| AuditStore.Save | p99 | 24ms | 22ms | -2ms | -8.18
| ChannelStore.GetGuestCount | p99 | 25ms | 23ms | -2ms | -8.09
| UserStore.AutocompleteUsersInChannel | p99 | 176ms | 165ms | -11ms | -6.24
| ChannelStore.GetMemberCount | p99 | 47ms | 45ms | -2ms | -4.22
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| searchPostsInTeam | avg | 36ms | 113ms | 77ms | 214.16
| saveReaction | avg | 9ms | 25ms | 16ms | 186.74
| viewChannel | avg | 9ms | 12ms | 3ms | 32.82
| setPostReminder | avg | 20ms | 25ms | 5ms | 25.57
| followThreadByUser | avg | 12ms | 15ms | 3ms | 25.31
| patchPost | avg | 25ms | 29ms | 4ms | 15.73
| getPostsForChannel | avg | 21ms | 23ms | 2ms | 9.65
| createDirectChannel | avg | 159ms | 168ms | 9ms | 5.66
| getAnalytics | avg | 42ms | 44ms | 2ms | 4.81
| createPost | avg | 146ms | 148ms | 2ms | 1.37
| addTeamMember | avg | 600ms | 607ms | 7ms | 1.17
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| patchPost | p99 | 49ms | 199ms | 150ms | 303.09
| root | p99 | 21ms | 43ms | 22ms | 102.80
| setPostReminder | p99 | 25ms | 50ms | 25ms | 100.60
| saveReaction | p99 | 28ms | 50ms | 22ms | 79.13
| getPublicChannelsForTeam | p99 | 25ms | 43ms | 18ms | 72.01
| searchPostsInTeam | p99 | 670ms | 965ms | 295ms | 44.03
| getFilePreview | p99 | 100ms | 138ms | 38ms | 38.05
| getPostsForChannel | p99 | 182ms | 209ms | 27ms | 14.81
| viewChannel | p99 | 30ms | 33ms | 3ms | 10.14
| getFileThumbnail | p99 | 99ms | 105ms | 6ms | 6.07
| getProfileImage | p99 | 465ms | 471ms | 6ms | 1.29
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getUsersByGroupChannelIds | avg | 4ms | 0s | -4ms | -103.58
| createCategoryForTeamForUser | avg | 23ms | 0s | -23ms | -100.97
| autocompleteChannelsForTeamForSearch | avg | 49ms | 40ms | -9ms | -18.54
| createChannel | avg | 222ms | 188ms | -34ms | -15.34
| createChannelBookmark | avg | 17ms | 15ms | -2ms | -11.67
| updateReadStateThreadByUser | avg | 35ms | 32ms | -3ms | -8.61
| searchAllChannels | avg | 37ms | 34ms | -3ms | -8.04
| createUser | avg | 190ms | 182ms | -8ms | -4.21
| login | avg | 105ms | 101ms | -4ms | -3.82
| removeUserCustomStatus | avg | 111ms | 109ms | -2ms | -1.80
| createGroupChannel | avg | 264ms | 260ms | -4ms | -1.51
| addChannelMember | avg | 163ms | 161ms | -2ms | -1.23
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getUsersByGroupChannelIds | p99 | 5ms | 0s | -5ms | -101.01
| getPrevTrialLicense | p99 | 5ms | 0s | -5ms | -101.01
| createCategoryForTeamForUser | p99 | 25ms | 0s | -25ms | -100.60
| getFilteredUsersStats | p99 | 25ms | 10ms | -15ms | -60.73
| searchAllChannels | p99 | 251ms | 100ms | -151ms | -60.25
| getDrafts | p99 | 18ms | 8ms | -10ms | -56.30
| updateCategoriesForTeamForUser | p99 | 216ms | 99ms | -117ms | -54.25
| createChannel | p99 | 495ms | 249ms | -246ms | -49.70
| deletePost | p99 | 48ms | 25ms | -23ms | -47.67
| getChannelUnread | p99 | 9ms | 5ms | -4ms | -47.06
| logout | p99 | 47ms | 25ms | -22ms | -46.55
| updateReadStateThreadByUser | p99 | 83ms | 50ms | -33ms | -39.59
| createDirectChannel | p99 | 399ms | 248ms | -151ms | -37.83
| getChannel | p99 | 16ms | 10ms | -6ms | -37.68
| getChannelMembersForTeamForUser | p99 | 16ms | 10ms | -6ms | -37.53
| listCPAValues | p99 | 19ms | 13ms | -6ms | -32.39
| getJobsByType | p99 | 7ms | 5ms | -2ms | -29.20
| getChannelsForTeamForUser | p99 | 14ms | 10ms | -4ms | -28.60
| upsertDraft | p99 | 15ms | 11ms | -4ms | -26.90
| getTeamsUnreadForUser | p99 | 39ms | 30ms | -9ms | -23.33
| getUser | p99 | 31ms | 24ms | -7ms | -22.29
| getTeamScheduledPosts | p99 | 38ms | 31ms | -7ms | -18.64
| getUsers | p99 | 29ms | 24ms | -5ms | -17.54
| getChannelMember | p99 | 48ms | 40ms | -8ms | -16.80
| autocompleteChannelsForTeamForSearch | p99 | 244ms | 210ms | -34ms | -13.93
| getTeamsForUser | p99 | 23ms | 20ms | -3ms | -13.19
| getCategoriesForTeamForUser | p99 | 40ms | 35ms | -5ms | -12.43
| getPostsForChannelAroundLastUnread | p99 | 91ms | 80ms | -11ms | -12.11
| autocompleteUsers | p99 | 159ms | 141ms | -18ms | -11.30
| getChannelStats | p99 | 28ms | 25ms | -3ms | -10.65
| getClientConfig | p99 | 48ms | 43ms | -5ms | -10.51
| listCPAFields | p99 | 39ms | 35ms | -4ms | -10.28
| getThreadsForUser | p99 | 22ms | 20ms | -2ms | -9.21
| getChannelsForUser | p99 | 23ms | 21ms | -2ms | -8.81
| getTeamMembersForUser | p99 | 24ms | 22ms | -2ms | -8.42
| getAllTeams | p99 | 24ms | 22ms | -2ms | -8.34
| addChannelMember | p99 | 403ms | 375ms | -28ms | -6.96
| createPost | p99 | 657ms | 613ms | -44ms | -6.70
| addTeamMember | p99 | 2.104s | 2.033s | -71ms | -3.38
| login | p99 | 491ms | 479ms | -12ms | -2.44
| createUser | p99 | 481ms | 472ms | -9ms | -1.87
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 5ms| 4ms | -1ms | -22.025
| |  P99| 24ms| 22ms | -2ms | -8.183
| BotStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -43.478
| ChannelBookmarkStore.Delete |  Avg| 8ms| 0s | -8ms | -95.724
| |  P99| 10ms| 0s | -10ms | -100.503
| ChannelBookmarkStore.Get |  Avg| 2ms| 0s | -2ms | -117.645
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 7ms | -1ms | -12.754
| ChannelBookmarkStore.Save |  Avg| 11ms| 10ms | -1ms | -9.188
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 22ms| 19ms | -3ms | -13.939
| ChannelStore.AnalyticsCountAll |  Avg| 21ms| 20ms | -1ms | -4.842
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.Autocomplete |  Avg| 37ms| 34ms | -3ms | -8.086
| |  P99| 251ms| 100ms | -151ms | -60.250
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 48ms| 39ms | -9ms | -18.565
| |  P99| 244ms| 210ms | -34ms | -13.934
| ChannelStore.CreateDirectChannel |  Avg| 23ms| 23ms | 0s | 0.000
| |  P99| 50ms| 64ms | 14ms | 28.173
| ChannelStore.CreateInitialSidebarCategories |  Avg| 18ms| 17ms | -1ms | -5.560
| |  P99| 76ms| 68ms | -8ms | -10.536
| ChannelStore.CreateSidebarCategory |  Avg| 20ms| 0s | -20ms | -100.016
| |  P99| 25ms| 0s | -25ms | -100.604
| ChannelStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 15ms | -4ms | -21.324
| ChannelStore.GetAllChannelMembersForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 19ms | -3ms | -13.480
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 12ms| 13ms | 1ms | 8.530
| |  P99| 82ms| 160ms | 78ms | 95.587
| ChannelStore.GetByName |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 38ms| 25ms | -13ms | -34.549
| ChannelStore.GetChannelUnread |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -47.056
| ChannelStore.GetChannels |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 14ms| 10ms | -4ms | -29.453
| ChannelStore.GetChannelsByUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 20ms | -3ms | -13.298
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 6ms | -2ms | -24.474
| ChannelStore.GetFileCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -44.162
| ChannelStore.GetForPost |  Avg| 2ms| 4ms | 2ms | 90.137
| |  P99| 5ms| 6ms | 1ms | 20.059
| ChannelStore.GetGuestCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 25ms| 23ms | -2ms | -8.088
| ChannelStore.GetMany |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMember |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 20ms | -3ms | -12.816
| ChannelStore.GetMemberCount |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 47ms| 45ms | -2ms | -4.216
| ChannelStore.GetMemberForPost |  Avg| 4ms| 20ms | 16ms | 388.122
| |  P99| 16ms| 35ms | 19ms | 121.779
| ChannelStore.GetMemberLastViewedAt |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 21ms| 16ms | -5ms | -24.033
| ChannelStore.GetMembersForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 16ms| 10ms | -6ms | -38.125
| ChannelStore.GetMembersForUserWithCursorPagination |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMembersForUserWithPagination |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 23ms| 22ms | -1ms | -4.321
| ChannelStore.GetPinnedPostCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetPublicChannelsForTeam |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 25ms| 28ms | 3ms | 12.002
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 35ms| 30ms | -5ms | -14.101
| ChannelStore.GetSidebarCategory |  Avg| 6ms| 7ms | 1ms | 15.907
| |  P99| 24ms| 24ms | 0s | 0.000
| ChannelStore.GetTeamChannels |  Avg| 17ms| 20ms | 3ms | 17.651
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.IncrementMentionCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 19ms| 15ms | -4ms | -21.423
| ChannelStore.Save |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 41ms| 33ms | -8ms | -19.394
| ChannelStore.SaveMember |  Avg| 31ms| 30ms | -1ms | -3.196
| |  P99| 122ms| 97ms | -25ms | -20.495
| ChannelStore.SearchGroupChannels |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 16ms| 17ms | 1ms | 6.085
| ChannelStore.UpdateLastViewedAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.128
| ChannelStore.UpdateSidebarCategories |  Avg| 36ms| 35ms | -1ms | -2.813
| |  P99| 89ms| 50ms | -39ms | -43.996
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 4ms| 3ms | -1ms | -25.241
| |  P99| 24ms| 11ms | -13ms | -55.231
| CommandWebhookStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ComplianceStore.MessageExport |  Avg| 3ms| 4ms | 1ms | 39.511
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Delete |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 7ms| 5ms | -2ms | -26.860
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| DraftStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.GetDraftsForUser |  Avg| 3ms| 2ms | -1ms | -37.669
| |  P99| 18ms| 7ms | -11ms | -61.992
| DraftStore.Upsert |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -9.628
| EmojiStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 8ms | 3ms | 57.159
| EmojiStore.GetMultipleByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.AttachToPost |  Avg| 7ms| 6ms | -1ms | -15.003
| |  P99| 22ms| 12ms | -10ms | -44.778
| FileInfoStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.GetByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 6ms | 1ms | 20.025
| FileInfoStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 19ms| 10ms | -9ms | -46.301
| FileInfoStore.SetContent |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 23ms| 14ms | -9ms | -39.706
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 16ms | -4ms | -20.307
| GroupStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 24ms| 22ms | -2ms | -8.377
| GroupStore.GetGroups |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 15ms| 13ms | -2ms | -13.229
| GroupStore.GetGroupsAssociatedToChannelsByTeam |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.GetAllByStatus |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 17ms| 9ms | -8ms | -48.273
| JobStore.GetAllByTypePage |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.GetCountByStatusAndType |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.GetNewestJobByStatusesAndType |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 21ms| 5ms | -16ms | -75.561
| JobStore.UpdateOptimistically |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 7ms| 15ms | 8ms | 109.589
| JobStore.UpdateStatus |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| JobStore.UpdateStatusOptimistically |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 17ms| 17ms | 0s | 0.000
| LicenseStore.GetAll |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Save |  Avg| 4ms| 3ms | -1ms | -27.026
| |  P99| 21ms| 6ms | -15ms | -72.114
| PostAcknowledgementStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostAcknowledgementStore.GetForPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 12ms| 10ms | -2ms | -17.327
| PostPersistentNotificationStore.DeleteExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.Get |  Avg| 3ms| 2ms | -1ms | -39.773
| |  P99| 9ms| 21ms | 12ms | 140.351
| PostPersistentNotificationStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 5ms | -2ms | -27.357
| PostPriorityStore.GetForPostWithContext |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPriorityStore.GetForPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 14ms| 13ms | -1ms | -7.086
| PostStore.AnalyticsPostCount |  Avg| 2ms| 138ms | 136ms | 6306.656
| |  P99| 5ms| 495ms | 490ms | 9895.427
| PostStore.AnalyticsPostCountByTeam |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Delete |  Avg| 16ms| 16ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| PostStore.Get |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 24ms| 22ms | -2ms | -8.441
| PostStore.GetEtag |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 16ms| 14ms | -2ms | -12.393
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 20ms| 15ms | -5ms | -25.048
| PostStore.GetPostIdBeforeTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 7ms | -1ms | -12.310
| PostStore.GetPostReminderMetadata |  Avg| 2ms| 5ms | 3ms | 126.176
| |  P99| 5ms| 10ms | 5ms | 100.964
| PostStore.GetPostReminders |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 9ms | -13ms | -57.906
| PostStore.GetPosts |  Avg| 4ms| 3ms | -1ms | -28.007
| |  P99| 22ms| 19ms | -3ms | -13.578
| PostStore.GetPostsAfter |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostsBefore |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.002
| PostStore.GetPostsByThread |  Avg| 5ms| 4ms | -1ms | -18.275
| |  P99| 22ms| 10ms | -12ms | -55.770
| PostStore.GetPostsSince |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 42ms| 41ms | -1ms | -2.378
| PostStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 49ms| 48ms | -1ms | -2.051
| PostStore.SearchPostsForUser |  Avg| 29ms| 107ms | 78ms | 271.845
| |  P99| 670ms| 964ms | 294ms | 43.881
| PostStore.SetPostReminder |  Avg| 7ms| 8ms | 1ms | 13.914
| |  P99| 10ms| 24ms | 14ms | 140.704
| PostStore.Update |  Avg| 12ms| 14ms | 2ms | 16.675
| |  P99| 25ms| 50ms | 25ms | 100.616
| PreferenceStore.DeleteCategoryAndName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -43.011
| PreferenceStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.468
| PreferenceStore.GetAll |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 22ms | -2ms | -8.222
| PreferenceStore.Save |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 55ms| 47ms | -8ms | -14.470
| ProductNoticesStore.GetViews |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 44ms| 41ms | -3ms | -6.854
| |  P99| 196ms| 165ms | -31ms | -15.835
| PropertyFieldStore.SearchPropertyFields |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 21ms| 17ms | -4ms | -19.213
| PropertyGroupStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 21ms| 18ms | -3ms | -14.282
| PropertyValueStore.SearchPropertyValues |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 12ms| 7ms | -5ms | -43.336
| ReactionStore.GetForPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 6ms| 7ms | 1ms | 15.806
| RetentionPolicyStore.GetAll |  Avg| 1ms| 0s | -1ms | -68.316
| |  P99| 5ms| 0s | -5ms | -101.010
| RetentionPolicyStore.GetCount |  Avg| 1ms| 0s | -1ms | -125.744
| |  P99| 5ms| 0s | -5ms | -101.010
| RoleStore.ChannelHigherScopedPermissions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 8ms | 3ms | 60.606
| RoleStore.GetByNames |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 21ms| 5ms | -16ms | -76.923
| ScheduledPostStore.CreateScheduledPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetMaxMessageSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetPendingScheduledPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.808
| ScheduledPostStore.GetScheduledPostsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 21ms| 19ms | -2ms | -9.474
| ScheduledPostStore.UpdateOldScheduledPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SchemeStore.GetAllPage |  Avg| 2ms| 0s | -2ms | -117.171
| |  P99| 5ms| 0s | -5ms | -101.010
| SessionStore.Get |  Avg| 6ms| 5ms | -1ms | -17.474
| |  P99| 42ms| 37ms | -5ms | -11.946
| SessionStore.GetLRUSessions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 22ms| 19ms | -3ms | -13.595
| SessionStore.GetSessionsExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.420
| SessionStore.Remove |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Save |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 41ms| 32ms | -9ms | -21.747
| SessionStore.UpdateLastActivityAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.158
| StatusStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 16ms | -4ms | -20.152
| StatusStore.GetByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.SaveOrUpdate |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 21ms| 21ms | 0s | 0.000
| StatusStore.SaveOrUpdateMany |  Avg| 7ms| 9ms | 2ms | 27.793
| |  P99| 25ms| 43ms | 18ms | 72.558
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 28ms| 8ms | -20ms | -72.072
| StatusStore.UpdateLastActivityAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.146
| SystemStore.GetByName |  Avg| 3ms| 2ms | -1ms | -37.683
| |  P99| 22ms| 19ms | -3ms | -13.712
| TeamStore.AnalyticsTeamCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -17.929
| TeamStore.GetActiveMemberCount |  Avg| 34ms| 34ms | 0s | 0.000
| |  P99| 50ms| 50ms | 0s | 0.000
| TeamStore.GetAllPage |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 22ms| 20ms | -2ms | -8.905
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 19ms | -3ms | -13.411
| TeamStore.GetMember |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 18ms | -3ms | -14.009
| TeamStore.GetTeamsByUserId |  Avg| 3ms| 2ms | -1ms | -38.949
| |  P99| 23ms| 20ms | -3ms | -13.332
| TeamStore.GetTeamsForUser |  Avg| 3ms| 2ms | -1ms | -38.087
| |  P99| 23ms| 20ms | -3ms | -13.319
| TeamStore.GetTotalMemberCount |  Avg| 34ms| 34ms | 0s | 0.000
| |  P99| 50ms| 50ms | 0s | 0.000
| TeamStore.SaveMember |  Avg| 25ms| 24ms | -1ms | -4.048
| |  P99| 82ms| 72ms | -10ms | -12.170
| TemporaryPostStore.GetExpiredPosts |  Avg| 3ms| 2ms | -1ms | -38.971
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ThreadStore.GetMembershipForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 7ms | -1ms | -12.404
| ThreadStore.GetTeamsUnreadForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 21ms | -3ms | -12.760
| ThreadStore.GetThreadFollowers |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.234
| ThreadStore.GetThreadForUser |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 24ms| 20ms | -4ms | -16.804
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 6ms| 5ms | -1ms | -17.670
| |  P99| 24ms| 21ms | -3ms | -12.627
| ThreadStore.GetThreadsForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.347
| ThreadStore.GetTotalThreads |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 16ms | -4ms | -19.957
| ThreadStore.GetTotalUnreadMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 16ms | -3ms | -16.068
| ThreadStore.GetTotalUnreadThreads |  Avg| 3ms| 2ms | -1ms | -39.940
| |  P99| 20ms| 17ms | -3ms | -15.158
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 3ms| 2ms | -1ms | -38.731
| |  P99| 20ms| 17ms | -3ms | -14.906
| ThreadStore.MaintainMembership |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 22ms| 20ms | -2ms | -8.994
| ThreadStore.MarkAllAsReadByChannels |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.MarkAllAsReadByTeam |  Avg| 4ms| 3ms | -1ms | -25.609
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.MarkAsRead |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| ThreadStore.UpdateMembership |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 7ms| 6ms | -1ms | -14.191
| TokenStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AnalyticsActiveCount |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AutocompleteUsersInChannel |  Avg| 34ms| 33ms | -1ms | -2.944
| |  P99| 176ms| 165ms | -11ms | -6.243
| UserStore.Count |  Avg| 12ms| 11ms | -1ms | -8.661
| |  P99| 47ms| 43ms | -4ms | -8.579
| UserStore.Get |  Avg| 3ms| 2ms | -1ms | -39.815
| |  P99| 17ms| 13ms | -4ms | -22.921
| UserStore.GetAllProfiles |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 20ms| 18ms | -2ms | -9.890
| UserStore.GetAllProfilesInChannel |  Avg| 148ms| 152ms | 4ms | 2.703
| |  P99| 473ms| 475ms | 2ms | 0.423
| UserStore.GetByUsername |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetForLogin |  Avg| 3ms| 2ms | -1ms | -37.491
| |  P99| 22ms| 19ms | -3ms | -13.715
| UserStore.GetMany |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.808
| UserStore.GetProfileByGroupChannelIdsForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfileByIds |  Avg| 3ms| 2ms | -1ms | -39.273
| |  P99| 18ms| 15ms | -3ms | -16.420
| UserStore.GetProfilesByUsernames |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 6ms | -2ms | -25.880
| UserStore.GetProfilesInChannel |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 25ms| 10ms | -15ms | -60.729
| UserStore.GetProfilesNotInChannel |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetUnreadCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| UserStore.IsEmpty |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 15ms| 10ms | -5ms | -33.333
| UserStore.Save |  Avg| 124ms| 121ms | -3ms | -2.421
| |  P99| 249ms| 248ms | -1ms | -0.402
| UserStore.Search |  Avg| 25ms| 25ms | 0s | 0.000
| |  P99| 50ms| 49ms | -1ms | -2.017
| UserStore.Update |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| UserStore.UpdateFailedPasswordAttempts |  Avg| 5ms| 4ms | -1ms | -21.592
| |  P99| 31ms| 23ms | -8ms | -25.719
| UserStore.UpdateLastLogin |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 23ms| 21ms | -2ms | -8.551
| UserStore.UpdateUpdateAt |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 23ms| 21ms | -2ms | -8.554
| UserTermsOfServiceStore.GetByUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 22ms| 20ms | -2ms | -9.204
| WebhookStore.GetOutgoingByTeam |  Avg| 4ms| 3ms | -1ms | -27.476
| |  P99| 22ms| 16ms | -6ms | -27.184
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 163ms| 161ms | -2ms | -1.230
| | P99| 403ms| 375ms | -28ms | -6.956
| addTeamMember | Avg| 600ms| 607ms | 7ms | 1.167
| | P99| 2.104s| 2.033s | -71ms | -3.375
| autocompleteChannelsForTeamForSearch | Avg| 49ms| 40ms | -9ms | -18.542
| | P99| 244ms| 210ms | -34ms | -13.934
| autocompleteUsers | Avg| 32ms| 31ms | -1ms | -3.154
| | P99| 159ms| 141ms | -18ms | -11.302
| createCategoryForTeamForUser | Avg| 23ms| 0s | -23ms | -100.970
| | P99| 25ms| 0s | -25ms | -100.604
| createChannel | Avg| 222ms| 188ms | -34ms | -15.339
| | P99| 495ms| 249ms | -246ms | -49.697
| createChannelBookmark | Avg| 17ms| 15ms | -2ms | -11.670
| | P99| 25ms| 25ms | 0s | 0.000
| createDirectChannel | Avg| 159ms| 168ms | 9ms | 5.662
| | P99| 399ms| 248ms | -151ms | -37.828
| createGroupChannel | Avg| 264ms| 260ms | -4ms | -1.513
| | P99| 496ms| 496ms | 0s | 0.000
| createPost | Avg| 146ms| 148ms | 2ms | 1.371
| | P99| 657ms| 613ms | -44ms | -6.701
| createSchedulePost | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| createUser | Avg| 190ms| 182ms | -8ms | -4.207
| | P99| 481ms| 472ms | -9ms | -1.871
| deleteDraft | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 9ms| 9ms | 0s | 0.000
| deletePost | Avg| 22ms| 22ms | 0s | 0.000
| | P99| 48ms| 25ms | -23ms | -47.666
| followThreadByUser | Avg| 12ms| 15ms | 3ms | 25.310
| | P99| 25ms| 25ms | 0s | 0.000
| getAgents | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getAgentsStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getAllTeams | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 24ms| 22ms | -2ms | -8.338
| getAnalytics | Avg| 42ms| 44ms | 2ms | 4.807
| | P99| 50ms| 50ms | 0s | 0.000
| getCategoriesForTeamForUser | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 40ms| 35ms | -5ms | -12.425
| getChannel | Avg| 4ms| 5ms | 1ms | 22.241
| | P99| 16ms| 10ms | -6ms | -37.678
| getChannelMember | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 48ms| 40ms | -8ms | -16.796
| getChannelMembersForTeamForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 16ms| 10ms | -6ms | -37.526
| getChannelMembersForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 23ms| 22ms | -1ms | -4.291
| getChannelStats | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 28ms| 25ms | -3ms | -10.654
| getChannelUnread | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 9ms| 5ms | -4ms | -47.056
| getChannelsForTeamForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 14ms| 10ms | -4ms | -28.600
| getChannelsForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 23ms| 21ms | -2ms | -8.811
| getClientConfig | Avg| 8ms| 7ms | -1ms | -12.894
| | P99| 48ms| 43ms | -5ms | -10.508
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getDrafts | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 18ms| 8ms | -10ms | -56.297
| getFilePreview | Avg| 44ms| 45ms | 1ms | 2.271
| | P99| 100ms| 138ms | 38ms | 38.054
| getFileThumbnail | Avg| 42ms| 43ms | 1ms | 2.356
| | P99| 99ms| 105ms | 6ms | 6.067
| getFilteredUsersStats | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 25ms| 10ms | -15ms | -60.728
| getGroups | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getJobsByType | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 7ms| 5ms | -2ms | -29.200
| getPostThread | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| getPostsForChannel | Avg| 21ms| 23ms | 2ms | 9.652
| | P99| 182ms| 209ms | 27ms | 14.814
| getPostsForChannelAroundLastUnread | Avg| 18ms| 17ms | -1ms | -5.521
| | P99| 91ms| 80ms | -11ms | -12.114
| getPreferences | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 24ms| 23ms | -1ms | -4.096
| getPrevTrialLicense | Avg| 1ms| 0s | -1ms | -89.471
| | P99| 5ms| 0s | -5ms | -101.010
| getProductNotices | Avg| 3ms| 2ms | -1ms | -36.986
| | P99| 5ms| 5ms | 0s | 0.000
| getProfileImage | Avg| 99ms| 99ms | 0s | 0.000
| | P99| 465ms| 471ms | 6ms | 1.290
| getPublicChannelsForTeam | Avg| 14ms| 14ms | 0s | 0.000
| | P99| 25ms| 43ms | 18ms | 72.014
| getRolesByNames | Avg| 2ms| 1ms | -1ms | -62.740
| | P99| 5ms| 5ms | 0s | 0.000
| getServerLimits | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 24ms| 25ms | 1ms | 4.098
| getTeamMember | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 8ms| 8ms | 0s | 0.000
| getTeamMembersForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 24ms| 22ms | -2ms | -8.423
| getTeamScheduledPosts | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 38ms| 31ms | -7ms | -18.635
| getTeamStats | Avg| 34ms| 34ms | 0s | 0.000
| | P99| 50ms| 50ms | 0s | 0.000
| getTeamsForUser | Avg| 3ms| 2ms | -1ms | -37.874
| | P99| 23ms| 20ms | -3ms | -13.195
| getTeamsUnreadForUser | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 39ms| 30ms | -9ms | -23.327
| getThreadsForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 22ms| 20ms | -2ms | -9.209
| getUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 31ms| 24ms | -7ms | -22.289
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 29ms| 24ms | -5ms | -17.541
| getUsersByGroupChannelIds | Avg| 4ms| 0s | -4ms | -103.577
| | P99| 5ms| 0s | -5ms | -101.010
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsersByNames | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 8ms| 7ms | -1ms | -12.485
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| handleCheckCWSConnection | Avg| 52ms| 51ms | -1ms | -1.931
| | P99| 99ms| 99ms | 0s | 0.000
| listCPAFields | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 39ms| 35ms | -4ms | -10.281
| listCPAValues | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 19ms| 13ms | -6ms | -32.388
| listChannelBookmarksForChannel | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 9ms| 8ms | -1ms | -11.092
| login | Avg| 105ms| 101ms | -4ms | -3.819
| | P99| 491ms| 479ms | -12ms | -2.442
| logout | Avg| 23ms| 22ms | -1ms | -4.372
| | P99| 47ms| 25ms | -22ms | -46.550
| patchPost | Avg| 25ms| 29ms | 4ms | 15.730
| | P99| 49ms| 199ms | 150ms | 303.090
| removeUserCustomStatus | Avg| 111ms| 109ms | -2ms | -1.800
| | P99| 247ms| 247ms | 0s | 0.000
| root | Avg| 2ms| 3ms | 1ms | 62.002
| | P99| 21ms| 43ms | 22ms | 102.804
| saveReaction | Avg| 9ms| 25ms | 16ms | 186.744
| | P99| 28ms| 50ms | 22ms | 79.130
| searchAllChannels | Avg| 37ms| 34ms | -3ms | -8.042
| | P99| 251ms| 100ms | -151ms | -60.250
| searchGroupChannels | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 18ms| 17ms | -1ms | -5.663
| searchPostsInTeam | Avg| 36ms| 113ms | 77ms | 214.158
| | P99| 670ms| 965ms | 295ms | 44.030
| searchUsers | Avg| 26ms| 26ms | 0s | 0.000
| | P99| 50ms| 49ms | -1ms | -2.014
| setPostReminder | Avg| 20ms| 25ms | 5ms | 25.569
| | P99| 25ms| 50ms | 25ms | 100.604
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 12ms| 13ms | 1ms | 8.036
| | P99| 25ms| 25ms | 0s | 0.000
| updateCategoriesForTeamForUser | Avg| 50ms| 51ms | 1ms | 1.997
| | P99| 216ms| 99ms | -117ms | -54.247
| updatePreferences | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 24ms| 24ms | 0s | 0.000
| updateReadStateAllThreadsByUser | Avg| 4ms| 3ms | -1ms | -25.034
| | P99| 5ms| 5ms | 0s | 0.000
| updateReadStateThreadByUser | Avg| 35ms| 32ms | -3ms | -8.609
| | P99| 83ms| 50ms | -33ms | -39.592
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 422ms| 423ms | 1ms | 0.237
| | P99| 992ms| 991ms | -1ms | -0.101
| upsertDraft | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 15ms| 11ms | -4ms | -26.895
| viewChannel | Avg| 9ms| 12ms | 3ms | 32.820
| | P99| 30ms| 33ms | 3ms | 10.138
